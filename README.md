<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Animes</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
    <header class="bg-indigo-600 text-white fixed w-full top-0 z-50 shadow-md">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center text-xl font-semibold">
                <img src="https://via.placeholder.com/40" alt="Logo do Site" class="mr-2 rounded-full">
                <span class="text-white">My Animes</span>
            </a>
            <nav class="hidden md:block">
                <ul class="flex space-x-6">
                    <li><a href="#destaques" class="hover:text-indigo-300 transition duration-300">Destaques</a></li>
                    <li><a href="#recomendacoes" class="hover:text-indigo-300 transition duration-300">Recomendações</a></li>
                    <li><a href="#noticias" class="hover:text-indigo-300 transition duration-300">Notícias</a></li>
                    <li><a href="#contato" class="hover:text-indigo-300 transition duration-300">Contato</a></li>
                </ul>
            </nav>
            <button id="menu-button" class="md:hidden text-white focus:outline-none" aria-label="Menu">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>
            </button>
        </div>
    </header>

    <div id="mobile-menu" class="hidden fixed top-0 left-0 w-full h-full bg-gray-900 bg-opacity-90 z-50">
        <div class="bg-gray-800 w-80 h-full absolute right-0 p-6">
            <div class="flex justify-end mb-4">
                <button id="close-menu-button" class="text-white focus:outline-none" aria-label="Fechar Menu">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                    </svg>
                </button>
            </div>
            <nav class="block">
                <ul class="space-y-4">
                    <li><a href="#destaques" class="block text-lg text-white hover:text-indigo-300 transition duration-300">Destaques</a></li>
                    <li><a href="#recomendacoes" class="block text-lg text-white hover:text-indigo-300 transition duration-300">Recomendações</a></li>
                    <li><a href="#noticias" class="block text-lg text-white hover:text-indigo-300 transition duration-300">Notícias</a></li>
                    <li><a href="#contato" class="block text-lg text-white hover:text-indigo-300 transition duration-300">Contato</a></li>
                </ul>
            </nav>
        </div>
    </div>

    <section id="destaques" class="pt-20 pb-10 bg-gradient-to-br from-indigo-100 to-purple-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold text-gray-800 text-center mb-8">Destaques da Temporada</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105">
                    <img src="https://via.placeholder.com/400x225" alt="Anime 1" class="w-full h-auto">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Anime 1: Título</h3>
                        <p class="text-gray-600 mb-3">Descrição do anime em destaque. Gênero, sinopse, etc.</p>
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105">
                    <img src="https://via.placeholder.com/400x225" alt="Anime 2" class="w-full h-auto">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Anime 2: Título</h3>
                        <p class="text-gray-600 mb-3">Descrição do anime em destaque. Gênero, sinopse, etc.</p>
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105">
                    <img src="https://via.placeholder.com/400x225" alt="Anime 3" class="w-full h-auto">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Anime 3: Título</h3>
                        <p class="text-gray-600 mb-3">Descrição do anime em destaque. Gênero, sinopse, etc.</p>
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <section id="recomendacoes" class="py-10 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold text-gray-800 text-center mb-8">Recomendações</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105 flex flex-col">
                    <img src="https://via.placeholder.com/400x225" alt="Anime 4" class="w-full h-auto">
                    <div class="p-4 flex-grow">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Anime 4: Título</h3>
                        <p class="text-gray-600 mb-3">Descrição do anime recomendado. Gênero, sinopse, etc.</p>
                    </div>
                    <div class="p-4">
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105 flex flex-col">
                    <img src="https://via.placeholder.com/400x225" alt="Anime 5" class="w-full h-auto">
                    <div class="p-4 flex-grow">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Anime 5: Título</h3>
                        <p class="text-gray-600 mb-3">Descrição do anime recomendado. Gênero, sinopse, etc.</p>
                    </div>
                    <div class="p-4">
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105 flex flex-col">
                    <img src="https://via.placeholder.com/400x225" alt="Anime 6" class="w-full h-auto">
                    <div class="p-4 flex-grow">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Anime 6: Título</h3>
                        <p class="text-gray-600 mb-3">Descrição do anime recomendado. Gênero, sinopse, etc.</p>
                    </div>
                    <div class="p-4">
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <section id="noticias" class="py-10 bg-indigo-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold text-gray-800 text-center mb-8">Últimas Notícias</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105 flex flex-col">
                    <img src="https://via.placeholder.com/400x225" alt="Notícia 1" class="w-full h-auto">
                    <div class="p-4 flex-grow">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Notícia 1: Título</h3>
                        <p class="text-gray-600 mb-3">Resumo da notícia. Detalhes sobre o evento, lançamento, etc.</p>
                        <span class="inline-block bg-indigo-200 text-indigo-700 px-2 py-1 rounded-full text-sm font-semibold mb-2">Categoria</span>
                    </div>
                    <div class="p-4">
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105 flex flex-col">
                    <img src="https://via.placeholder.com/400x225" alt="Notícia 2" class="w-full h-auto">
                    <div class="p-4 flex-grow">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Notícia 2: Título</h3>
                        <p class="text-gray-600 mb-3">Resumo da notícia. Detalhes sobre o evento, lançamento, etc.</p>
                        <span class="inline-block bg-indigo-200 text-indigo-700 px-2 py-1 rounded-full text-sm font-semibold mb-2">Categoria</span>
                    </div>
                    <div class="p-4">
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
                <article class="bg-white rounded-lg shadow-md overflow-hidden transition-transform duration-300 hover:shadow-lg hover:scale-105 flex flex-col">
                    <img src="https://via.placeholder.com/400x225" alt="Notícia 3" class="w-full h-auto">
                    <div class="p-4 flex-grow">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Notícia 3: Título</h3>
                        <p class="text-gray-600 mb-3">Resumo da notícia. Detalhes sobre o evento, lançamento, etc.</p>
                        <span class="inline-block bg-indigo-200 text-indigo-700 px-2 py-1 rounded-full text-sm font-semibold mb-2">Categoria</span>
                    </div>
                    <div class="p-4">
                        <a href="#" class="inline-flex items-center text-indigo-500 hover:text-indigo-700 transition duration-300">
                            Ver mais
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 ml-1">
                                <path fill-rule="evenodd" d="M12.2 3.29a.75.75 0 011.06 1.06L8.06 10.94a3 3 0 1 0-4.24 4.24l7.64-7.64a.75.75 0 011.06 1.06h.02z" clip-rule="evenodd" />
                            </svg>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <section id="contato" class="py-10 bg-indigo-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold text-gray-800 text-center mb-8">Contato</h2>
            <div class="bg-white rounded-lg shadow-md p-8 max-w-md mx-auto">
                <form>
                    <div class="mb-4">
                        <label for="nome" class="block text-gray-700 text-sm font-bold mb-2">Nome:</label>
                        <input type="text" id="nome" name="nome" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline">
                    </div>
                    <div class="mb-4">
                        <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Email:</label>
                        <input type="email" id="email" name="email" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline">
                    </div>
                    <div class="mb-4">
                        <label for="mensagem" class="block text-gray-700 text-sm font-bold mb-2">Mensagem:</label>
                        <textarea id="mensagem" name="mensagem" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline h-32 resize-y"></textarea>
                    </div>
                    <button type="submit" class="bg-indigo-500 hover:bg-indigo-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">Enviar Mensagem</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-4">
        <div class="container mx-auto px-4 text-center">
            <p>© 2024 My Animes. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script>
        const menuButton = document.getElementById('menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        const closeMenuButton = document.getElementById('close-menu-button');
        const mobileMenuLinks = mobileMenu.querySelectorAll('a');
        const navLinks = document.querySelectorAll('.nav-links a');
        const sections = document.querySelectorAll('section');

        function toggleMobileMenu() {
            mobileMenu.classList.toggle('hidden');
        }

        menuButton.addEventListener('click', toggleMobileMenu);
        closeMenuButton.addEventListener('click', toggleMobileMenu);
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', toggleMobileMenu);
        });

        document.addEventListener('click', (event) => {
            if (!mobileMenu.classList.contains('hidden') && !mobileMenu.contains(event.target) && event.target !== menuButton) {
                toggleMobileMenu();
            }
        });

        function updateActiveNavLink() {
            let currentSectionId = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (window.scrollY >= sectionTop - 100 && window.scrollY < sectionTop + sectionHeight - 100) {
                    currentSectionId = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('active');
                if(link.getAttribute('href').slice(1) === currentSectionId) {
                    link.classList.add('active');
                }
            });
        }

        window.addEventListener('scroll', updateActiveNavLink);

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
