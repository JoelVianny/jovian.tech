<script>
    import {A} from "flowbite-svelte";
    import MailIcon from "../assets/icons/mail.svg";
    import TelegramIcon from "../assets/icons/telegram.svg";
    import GithubIcon from "../assets/icons/github.svg";
    import LinkIcon from "../assets/icons/link.svg";
</script>

<div class="content py-7">
    <div class="text-center">
        <p class="text-5xl font-bold text-black dark:text-white">JovianTech</p>
        <p class="text-2xl text-black dark:text-white">Software Engineer</p>
    </div>
    <div class="py-10 w-full md:w-1/2 mx-auto">
        <p class="text-black text-lg dark:text-white">
My name is Joel Vianny
         I am a Software Engineer 
            <A href="" aClass="inline-flex items-center font-medium">
                Entry Level <LinkIcon class="p-0.5 m-0.5 h-5 w-5"/>
            </A>
           
        </p>
        <p class="text-black dark:text-white font-medium py-2">
            I specialize in backend technologies and have a strong passion for coding, learning, 
            and applying algorithms, data structures, and architectural design. I thoroughly enjoy exploring
             all aspects of computer science and constantly strive to expand my knowledge in the field.
    </div>

    <div class="py-5 flex items-center mx-auto justify-center space-x-8">
        <a class="text-primary-600" href="//github.com/JoelVianny/" target="_blank">
            <GithubIcon class="w-5 h-5"/>
        </a>
        <a class="text-primary-600" href="//t.me/jovian_tech" target="_blank">
            <TelegramIcon class="w-5 h-5"/>
        </a>
        <a class="text-primary-600" href="mailto:jvmpegna@yahoo.com" target="_blank">
            <MailIcon class="w-5 h-5"/>
        </a>
    </div>
</div>
