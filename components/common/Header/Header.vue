<template>
    <header class="header" id="header">
        <div class="header-menu">
			<div class="container">
				<div class="row navigation no-gutters d-flex">
					<div class="col-lg-4">
						<div class="header__adress">
							Владивосток, ул. Днепровская, 21
						</div>
                    </div>
                    <a class="logo col-lg-4" href="#">
                        <img src="#" alt="логотип">
                    </a>
                    <a href="tel:+79108900001" class="phone align-items-center col-lg-4">
                        <p>
                            +7 (910) 890 0001
                        </p>
                    </a>
                </div>
                    <div class="col-lg-10 ml-auto">
						<nav>
							<ul class="menu d-flex">
								<li class="menu__item">
									<a href="#type">
										Отзывы                   
									</a>								
								</li>
								<li class="menu__item">
									<a href="#dop">
							             Контакты                  
									</a>								
								</li>
								<li class="menu__item">
									<a href="#about">
									    Обзоры                   
									</a>								
								</li>
								<li class="menu__item">
									<a href="#gallery">
										Консультация
									</a>								
								</li>
							</ul>
						</nav>
					</div>
			</div>
		</div>
    </header>
</template>

<script>

export default {
    name: "Header",
}

</script>

<style src="./style.css" scoped></style>