<script></script>
<template>
    <header>
        <div class="container">
            <div class="row align-items-center justify-content-between">
                <div class="col">
                    <p class="m-0">Serena Dong</p>
                    <p id="location" class="text-secondary m-0">Milan, Italy</p>
                </div>
                <div class="col">
                    <nav>
                        <ul class="d-flex gap-3 justify-content-center bg-white py-3 rounded-5 m-0">
                            <li><a href="">Home</a></li>
                            <li><a href="">Work</a></li>
                            <li><a href="">About</a></li>
                            <li><a href="">Contacts</a></li>
                        </ul>
                    </nav>
                </div>
                <div class="col social text-end">
                    <p class="text-secondary m-0">Social:</p>
                    <ul class="d-flex gap-3 justify-content-end text-end m-0 ">
                        <li><a href="https://www.linkedin.com/in/serena-dong-500877240/">LKDN</a></li>
                        <li><a href="https://github.com/Serena-Dong">GIT</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss" scoped>
header .row {
    min-height: 100px;

    nav ul a {
        color: black;
        padding: 1rem;

        &:hover {
            color: white;
            background-color: black;
            padding: 1rem;
            border-radius: 50px;

            transition-duration: 1s;
            transition-property: background-color;
        }
    }

    .social {
        p {
            font-size: 0.9rem;
        }

        ul li a {
            font-size: 0.8rem;
            color: black;

            &:hover {
                color: grey;

                transition-duration: 200ms;
                transition-property: color;
            }
        }
    }
}
</style>