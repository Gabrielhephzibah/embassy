<template>
	<div class="wrapper">
		<div class="text3">
			<ul class="text2 ">
				<li>Home</li>
				<li> policy details</li>
				<li>My Member</li>
				<li>E-Card</li>
				<li> Network Empires</li>
				<li>Change password</li>
				<li> Log Out</li>
			</ul>
		</div>


		<div class="text">
			<h1>A Good smile and a Long Sleep</h1>
			<h5>are the best cures in the Doctor's book</h5>
		</div>
		<div class="head">
			<div class="first" id="green">
				<img class="img"src="../assets/network.png" >
				<h4  class="imgText">Network</h4>
				
			</div>
			<div class="first ml-5" id="blue">
				<router-link :to="{name:'form'}">
				<img class="img" src="../assets/worker.png">
				<h4 class="imgText" style="padding-top:20px;">Employee</h4>
			</router-link>
			</h4>
				
			</div>
			<div class="first ml-5 " id="red">
				<img class="img" src="../assets/sun.png" style="padding-top:12px;">
				<h4 class="imgText" style="padding-top:4px;">Human Resources</h4>
				
			</div>
			
		</div>

		
	</div>
	
</template>



<style scoped>
	.wrapper{
		background-color: #3B3F4F;
		height: 100vh; 
	}

	.text{
		color: #ffff;
		padding-top: 100px;
	}
	.text3{
		width:50%;
		float: right;
	}
	.text2{
		color: #ffff;
		display: right;

		display: flex;
	justify-content: space-between;
list-style: none;
font-size: 12px;
font-family: sans-serif;
		
	 
	}

	.head{
		display: flex;
	}

	.first{
		height: 150px;
		width: 150px;
		background-color: red;


	}
	.head{
		margin-top: 120px;
		margin-left: 400px;
	}

	#green{
		background-color: #946A66;
	}

	#blue{
		background-color: #36395F;


	}
	#red{
		background-color: #336184;
	}
	.img{
		padding-top:16px;

	}
	.imgText{
		font-size:18px; 
		padding-top:25px;
		color: #ffff;
		font-weight: 30px;
	}




</style>