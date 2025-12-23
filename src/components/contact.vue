<template id="Contact" >

    <!-- Background Shapes -->
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
    <div class="shape shape3"></div>

    <v-container class="mt-10 ">

        <h2 class="contact-title">Let's Work Together</h2>


        <v-row justify="center "  class="link-item  align-center text-white  text-h5 pb-16" >

<v-col cols="12" class="text-center gap-2 d-flex justify-center" style="gap: 40px; ">

    <v-icon @click="openLink('https://www.linkedin.com/in/muhammed-haitham/')" class="social-icon">
        mdi-linkedin
    </v-icon>
    <v-icon  @click="openLink('tel:+201205464703')" class="social-icon">
        mdi-phone
    </v-icon>
    <v-icon  @click="openLink('mailto:mohamedhaithem240@gmail.com')" class="social-icon">
        mdi-gmail
    </v-icon>
</v-col>
             <v-col cols="12" class="text-center"> 
                <v-btn class="text-none" prepend-icon="mdi-whatsapp" rounded="lg"  color="green-darken-1" @click="openLink(`https://wa.me/201205464703`)">
                    Chat on what'sapp
                </v-btn>
             </v-col>   
                
            </v-row>

        <v-row>

            <v-col>
                <div class="text-center text-white">
                    <p>&copy; 2025 Mohamed Haitham. All rights reserved.</p>
                </div>
            </v-col>
        </v-row>

    </v-container>
</template>

<script>
import emailjs from 'emailjs-com';

export default {
    data() {
        return {
            form: {
                name: "",
                email: "",
                message: ""
            }
        }
    },
    methods: {
        openLink(url) {
            window.open(url, "_blank");
        },
        async sendEmail() {
            const params = {
                from_name: this.form.name,
                from_email: this.form.email,
                message: this.form.message
            };

            try {
                await emailjs.send(
                    "service_1knd85o",
                    "template_o779c3a",
                    params,
                    "v8nsuu2UQjSZR2oU3"
                );
                alert("Message sent successfully!");
                this.form = { name: "", email: "", message: "" };
            } catch (err) {
                console.error(err);
                alert("Failed to send message.");
            }
        }
    }
};
</script>
<style scoped>
/* ======= CONTACT SECTION ======= */
.contact-section {
    width: 100%;
    padding: 100px 0;
    background: linear-gradient(135deg, #0d48a156, #1e88e55e);
    display: flex;
    justify-content: center;
    align-items: center;
}
.social-icon:hover{
    transition: 0.5s all ease-in-out;
    color:#00838F

}

/* Title */
.contact-title {
    text-align: center;
    font-size: 40px;
    font-weight: bold;
    color: #fff;
    margin-bottom: 40px;
    letter-spacing: 1px;
    text-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
}

/* ======= FORM CONTAINER ======= */
.contact-form {
    padding: 35px;
    border-radius: 18px;
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(18px);
    box-shadow: 0 0 30px rgba(255, 255, 255, 0.12);
    animation: fadeInUp 1s ease;
}

/* Animation */
@keyframes fadeInUp {
    from {
        transform: translateY(40px);
        opacity: 0;
    }

    to {
        transform: translateY(0);
        opacity: 1;
    }
}

/* ======= INPUTS ======= */
.input-group {
    position: relative;
    margin-bottom: 28px;
}

.input-group input,
.input-group textarea {
    width: 100%;
    padding: 14px 12px;
    border: none;
    border-bottom: 2px solid #ddd;
    background: transparent;
    outline: none;
    color: #fff;
    font-size: 16px;
    transition: 0.3s;
    resize: none;
}

/* Textarea height */
.textarea-group textarea {
    height: 120px;
}

/* Floating labels */
.input-group label {
    position: absolute;
    left: 10px;
    top: 14px;
    color: #eee;
    pointer-events: none;
    transition: 0.3s ease;
}

/* When active or filled */
.input-group input:focus,
.input-group textarea:focus {
    border-color: #90caf9;
}

.input-group input:focus+label,
.input-group textarea:focus+label,
.input-group input:not(:placeholder-shown)+label,
.input-group textarea:not(:placeholder-shown)+label {
    top: -10px;
    font-size: 12px;
    color: #90caf9;
}

/* ======= SEND BUTTON ======= */
.send-btn {
    padding: 14px;
    font-size: 17px;
    border-radius: 12px;
    background: #fff !important;
    color: #0d47a1 !important;
    font-weight: bold;
    transition: 0.3s ease;
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.4);
}

.send-btn:hover {
    background: #e3f2fd !important;
    transform: translateY(-3px);
    box-shadow: 0 6px 18px rgba(255, 255, 255, 0.5);
}
</style>