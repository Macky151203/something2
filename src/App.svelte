<script>

</script>
<main>
    <div class="navbar">
		<div class="searchbar">
			<div class="right">
				
			</div>
		</div>
    </div>

	<div class="secondcontainer">
		<div class="wrapper">
			<div class="static-text">I em</div>
			<div class="dynamic-text">
				<div class="li"><span>Get access to...</span></div>
				<div class="li"><span>Notes, Uniform...</span></div>
				<div class="li"><span>And Stationery...</span></div>
				
			</div>
				
				
				

		</div>
	</div>


	<div class="title1">
		<h2> FEATURED PRODUCTS </h2>
	</div>
	<div class="cards1">
		<div class="card">
			<div class="item"></div>
			<div class="item"></div>
			<div class="item"></div>
			<div class="item"></div>
		</div>
	</div>
	<div class="cards1">
		<div class="card">
			<div class="item"></div>
			<div class="item"></div>
			<div class="item"></div>
			<div class="item"></div>
		</div>
	</div>
	<div class="title1">
		<h2> TRENDING PRODUCTS </h2>
	</div>
	<div class="cards1">
		<div class="card">
			<div class="item"></div>
			<div class="item"></div>
			<div class="item"></div>
			<div class="item"></div>
		</div>
	</div>

	<div class="footer">
		<div class="fcont">
		<div class="fitem">
			<div class="logo">
				LOGO
			</div>
			<div class="fgrid">
				<div class="gitem"></div>
				<div class="gitem"></div>
				<div class="gitem"></div>
				<div class="gitem"></div>
			</div>
		</div>
		<div class="fitem"></div>
		<div class="fitem"></div>
		<div class="fitem"></div>
	</div>
		
	</div>
</main>
<style>
    *{
        max-width: 100vw;
        max-height: 100vh;
		margin: 0;
		padding: 0;
    }
    .navbar{
        width: 100vw;
        height: 50px;
		background-color: rgb(62, 176, 247);
		display: flex;
		justify-content: center;
		align-items: center;
    }
	.searchbar{
		width: 40vw;
		height: 40px;
		background-color: white;
		border-radius: 20px;
	}
	.right{
		width: 50px;
		height: 40px;
		float: right;
		background-color: yellow;
		border-top-right-radius: 20px;
		border-bottom-right-radius: 20px;


	}
	.title1{
		margin: 30px;
	}
	.secondcontainer{
		width: 100vw;
		height: 100px;
		background-color: white;
		margin: 10px;
		padding: 10px;
		display: flex;
		justify-content: center;
	}
	.wrapper{
		display: inline-flex;
	}
	.wrapper .static-text{
		color: white;
		font-size: 60px;
		font-weight: 400;
		font-family: fantasy;

	}
	.wrapper .dynamic-text{
		margin-left: 10px;
		overflow: hidden;
		line-height: 90px;
		height: 90px;
	}
	.dynamic-text .li{
		font-family: fantasy;
		list-style: none;
		font-size: 50px;
		font-weight: 500;
		color: black;
		position: relative;
		top: 0px;
		/* left: 0px; */
		text-align: left;
		animation: slide 6s steps(3) infinite;
		z-index: 1;
		
	}
	@keyframes slide{
		100%{
			top: -270px;
		}

	}
	.dynamic-text .li span{
		position: relative;
		

	}
	.dynamic-text .li span::after{
		content:"";
		position: absolute;
		top: 0px;
		left: 0;
		height: 100%;
		width: 100%;
		border-left: 2px solid black;
		animation: typing 2s steps(30) infinite ;
		background: white;
		z-index: 1;
	}
	@keyframes typing{
		100%{
			left: 100%;
			margin: 0 -35 0 35px;
		}
	}
	.cards1{
		margin: 30px;
		padding: 10px;
	}
	.card{
		display: grid;
		grid-template-rows: repeat(1,1fr);
		grid-template-columns: repeat(4,1fr);
		column-gap: 40px;
		height: 250px;
		min-width: 80px;
		
		
	}
	.item{
		background-color: whitesmoke;
		border-radius: 10px;
		box-shadow: 2px 2px 2px 2px grey;
	}
	.footer{
		height: 300px;
		width: 100vw;
		background-color:  rgb(62, 176, 247);
		margin-top: 60px;
		padding: 15px;
		
	}
	.fcont{
		display: grid;
		grid-template-columns: repeat(4,1fr);
		grid-template-rows: repeat(1,1fr);
		column-gap: 15px;
		height: 300px;
		min-width: 80px;
		
	}
	.fitem{
		background-color: grey;
		
	}
	.logo{
		font-size: 2rem;
		text-align: center;
		position: relative;
		top: 25px;

	}
	.fgrid{
		display: grid;
		grid-template-columns: repeat(4,1fr);
		grid-template-rows: repeat(1,1fr);
		column-gap: 1px;
		position: relative;
		top: 60px;
		margin-left: 15px;
	}
	.gitem{
		width: 50px;
		height: 50px;
		background-color: white;
	}
</style>
