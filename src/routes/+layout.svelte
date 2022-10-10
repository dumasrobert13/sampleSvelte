<script>
    import "../app.postcss";
</script>
<main class="bg-gradient-to-br from-[#0f2027] via-[#203a43] to-[#2c5364] h-screen">
    <nav class="bg-blue-900 shadow-lg">
        <div class="container mx-auto">
            <div class="sm:flex">
                <a href="/" class="text-white text-3x1 font-bold p-3 text-xl">Sample</a>

                <!-- menu -->
                <div class="ml-55 sm:flex">
                    <ul class="text-white sm:self-center text-xl">
                        <li class="sm:inline-block">
                            <a href="/about" class="p-3 hover-1">About</a>
                        </li>
                        <li class="sm:inline-block">
                            <a href="/blog" class="p-3 hover-1">Blog</a>
                        </li>
                    </ul>
                </div>

            </div>
        </div>
    </nav>
<slot></slot>
</main>
