<script>
    import Project from "../lib/Project.svelte";
</script>

<div class="content mt-20">
    <div class="text-center">
        <p class="text-5xl font-bold text-black dark:text-white">Projects</p>
        <p class="text-xl py-1 font-light text-black dark:text-white">
            A collection of somr  projects I've participated in creating or of which I am the main contributor.</p>
    </div>
    <div class="mt-10 grid  md:grid-cols-3">
        <Project url="https://github.com/JoelVianny/Spring-Boot-Export-Data-to-Excel.git" title={"Export data to Excel"} tags={["Spring Boot ,Java "]}>
            A Spring Boot Export Data to Excel application allows users to export data from a database 
            or application into Excel spreadsheet files (.xlsx or .xls format).
             This type of application is widely used in scenarios where structured data needs to be analyzed, 
             shared, or archived.
        </Project>
        <Project url="https://github.com/JoelVianny/Spring-Crud-with-GrapQL.git" title={"GrapQL"} tags={["Java,GraphQL,Spring"]}>
            A Spring CRUD with GraphQL application allows users to perform Create, Read, Update, and
             Delete (CRUD) operations on data using GraphQL, a query language for APIs that provides flexible and efficient data fetching.
        </Project>
        <Project url="https://github.com/JoelVianny/Spring-migration-with-Flyway-.git" title={"Flyway"} tags={["Java", " Flyway"]}>
           Spring Migration with Flyway is a powerful approach to managing and automating database migrations in Spring applications.
        </Project>
        <Project url="https://github.com/JoelVianny/product-service.git" title={"Microservice"} tags={["Java ", "Spring Cloud "]}>
           A Product Service in the context of microservices is a standalone service that manages product-related data and functionality.
        </Project>
        
    <Project url="https://github.com/JoelVianny/jwt-auth-new.git" title={"Jwt Auth with last updates"} tags={["Java", "Spring security"]}>
       The JWT-Auth-New project typically refers to an application  that implements JWT-based authentication using JSON Web Tokens (JWT) to secure communication between clients and servers
        </Project>
       
    </div>
</div>
