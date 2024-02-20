


<template>
  
  <header>
			<h1>!Móvil</h1>

			<div class="container-icon">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="icon-cart"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z"
					/>
				</svg>
				<div class="count-products">
					<span id="contador-productos">0</span>
				</div>

				<div class="container-cart-products hidden-cart">
					<div class="cart-product">
						<div class="info-cart-product">
                            <span class="cantidad-producto-carrito">1</span>
                            <p class="titulo-producto-carrito">Zapatos Nike</p>
                            <span class="precio-producto-carrito">$80</span>
                        </div>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke-width="1.5"
							stroke="currentColor"
							class="icon-close"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M6 18L18 6M6 6l12 12"
							/>
						</svg>
					</div>
                    <div class="cart-total">
                        <h3>Total:</h3>
                        <span class="total-pagar">$200</span>
                    </div>
				</div>
			</div>
		</header>
		<div class="container-items">
			<div class="item">
				<figure>
					<img
						src="https://i5.walmartimages.com.mx/mg/gm/3pp/asr/1d333b4c-9c37-4700-8b10-d8198492da4a.3f85580cfdfae46f63fe7db5feddffc3.webp?odnHeight=612&odnWidth=612&odnBg=FFFFFF"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Iphone 15 128 gb</h2>
          <p class="price">$14,999</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Audifonos</h2>
					<p class="price">$20</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1099&q=80"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Reloj</h2>
					<p class="price">$50</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="https://images.unsplash.com/photo-1546868871-7041f2a55e12?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Smartwatch</h2>
					<p class="price">$90</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
			<div class="item">
				<figure>
					<img
						src="data:image/jpeg;base64,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"
						alt="producto"
					/>
				</figure>
				<div class="info-product">
					<h2>Galaxy tab</h2>
					<p class="price">$8999</p>
					<button>Añadir al carrito</button>
				</div>
			</div>
		</div>
</template>
<style>
*::after,
*::before,
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    margin: 0 auto;
    max-width: 1200px;
    font-family: 'Lato';
    color: #333;
}

.icon-cart{
    width: 40px;
    height: 40px;
    stroke: #000;
}

.icon-cart:hover{
    cursor: pointer;
}

img{
    max-width: 100%;
}

/* Header */
header{
    display: flex;
    justify-content: space-between;
    padding: 30px 0 40px 0;
}

.container-icon{
    position: relative;
}

.count-products{
    position: absolute;
    top: 55%;
    right: 0;

    background-color: #000;
    color: #fff;
    width: 25px;
    height: 25px;

    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
}

#contador-productos{
    font-size: 12px;
}

.container-cart-products{
    position: absolute;
    top: 50px;
    right: 0;

    background-color: #fff;
    width: 400px;
    z-index: 1;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.20);
    border-radius: 10px;
    
}

.cart-product{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 30px;

    border-bottom: 1px solid rgba(0, 0, 0, 0.20);

}

.info-cart-product{
    display: flex;
    justify-content: space-between;
    flex: 0.8;
}

.titulo-producto-carrito{
    font-size: 20px;
}

.precio-producto-carrito{
    font-weight: 700;
    font-size: 20px;
    margin-left: 10px;
}

.cantidad-producto-carrito{
    font-weight: 400;
    font-size: 20px;
}

.icon-close{
    width: 25px;
    height: 25px;
}

.icon-close:hover{
    stroke: red;
    cursor: pointer;
}

.cart-total{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px 0;
    gap: 20px;
}

.cart-total h3{
    font-size: 20px;
    font-weight: 700;
}

.total-pagar{
    font-size: 20px;
    font-weight: 900;
}

.hidden-cart{
    display: none;
}




/* Main */
.container-items{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.item{
    border-radius: 10px;
}

.item:hover{
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.20);
}

.item img{
    width: 100%;
    height: 300px;
    object-fit: cover;
    border-radius: 10px 10px 0 0;
    transition: all .5s;
}

.item figure{
    overflow: hidden;
}
.item:hover img{
    transform: scale(1.2);
}

.info-product{
    padding: 15px 30px;
    line-height: 2;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.price{
    font-size: 18px;
    font-weight: 900;
}

.info-product button{
    border: none;
    background: none;
    background-color: #000;
    color: #fff;
    padding: 15px 10px;
    cursor: pointer;
}

	</style>
