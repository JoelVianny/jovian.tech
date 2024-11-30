<script>
    import {
        Navbar,
        NavLi,
        NavUl,
        NavHamburger,
        DarkMode, Button
    } from 'flowbite-svelte';
    import CvIcon from "../assets/icons/cv.svg";
    import NavbarItem from "./NavbarItem.svelte";
    	import PdfViewer from 'svelte-pdf';

    
</script>

<Navbar class="fixed top-0 start-0 bg-transparent dark:bg-transparent">
    <NavHamburger/>
    <NavUl ulClass="flex flex-col p-4 mt-4 md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:text-sm md:font-medium items-center">
        <NavLi>
            <DarkMode/>
        </NavLi>
        <NavbarItem url="/">Home</NavbarItem>
        <NavbarItem url="/projects">Projects</NavbarItem>
        <NavLi>
<a href="" target="_blank" rel="noopener noreferrer">      <PdfViewer  url="/src/assets/icons/cv.pdf"/>          <Button>
                    CV
                    <CvIcon class="p-0.5 ml-0.5 h-5 w-5"/>
                </Button>
            </a>
        </NavLi>
    </NavUl>
</Navbar>
