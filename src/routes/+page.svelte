<script>
	import '../app.css';
	import logo from '$lib/assets/logo.png';
</script>

<body>
	<header
		class="w-full
  h-screen
  max-h-[32rem]
  p-24
  relative
  overflow-hidden
  block
  z-10
  
  bg-[url('https://www.cnnbrasil.com.br/viagemegastronomia/wp-content/uploads/sites/5/2023/02/St.-Chico_Vitrine-Almoco-01_Wellington-Nemeth.jpg?w=1220&h=674&crop=1')]
  bg-cover
  bg-no-repeat
  bg-center

  before:content-['']
  before:absolute
  before:inset-0
  before:block
  before:bg-gradient-to-r
  before:from-[#381717]
  before:to-[#5c2626]
  before:opacity-70
  before:z-[-5]
"
	>
		<div class="navbar -mt-20">
			<div class="flex-1">
				<a href="/"
					><button
						class="btn btn-outline bg-cover bg-center bg-[url('$lib/assets/logo.png')] w-24 h-24"
					>
					</button></a
				>
			</div>
			<div class="flex-none">
				<ul class="menu menu-horizontal px-1">
					<li class="text-white text-lg font-poppins"><a href="/">Início</a></li>
					<li class="text-white text-lg font-poppins"><a href="/about">Sobre</a></li>
					<li class="text-white text-lg font-poppins"><a href="/contacts">Contatos</a></li>
					<li class="text-white text-lg font-poppins"><a href="/products">Produtos</a></li>
				</ul>
			</div>
		</div>
		<h1 class="text-4xl mt-28 text-white font-poppins font-extrabold">
			A Padaria A&E é uma das melhores padarias de São Paulo. Nós providenciamos produtos de boa
			qualidade para satisfazermos os nosso clientes
		</h1>
	</header>
</body>

<slot />
