<template>
	<div  class="mainbg">
		<b-navbar toggleable="lg" type="dark" variant="primary">
			<b-navbar-brand class="text-monospace" href="#"><h3>LIS</h3></b-navbar-brand>

			<b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

			<b-collapse id="nav-collapse" is-nav>
				<b-navbar-nav class="mx-5">
					<b-nav-item-dropdown text="File">
						<b-dropdown-item href="#">Login</b-dropdown-item>
						<b-dropdown-item href="#">Backup</b-dropdown-item>
						<b-dropdown-item href="#">Change Password</b-dropdown-item>
						<b-dropdown-item href="#">Logout</b-dropdown-item>
					</b-nav-item-dropdown>
					<b-nav-item-dropdown text="Setup">
						<b-dropdown-item href="#">Lab Departments</b-dropdown-item>
						<b-dropdown-item href="#">Lab Machines</b-dropdown-item>
						<b-dropdown-item href="#">Jobs</b-dropdown-item>
						<b-dropdown-item href="#">Customers</b-dropdown-item>
						<b-dropdown-item href="#">Customers Pricelist</b-dropdown-item>
						<b-dropdown-item href="#">Lab Groups</b-dropdown-item>
						<b-dropdown-item href="#">Test Units</b-dropdown-item>
						<b-dropdown-item href="#">Test Types</b-dropdown-item>
						<b-dropdown-item href="#">Lab Tests</b-dropdown-item>
						<!-- <b-nav-item-dropdown right>
						<template v-slot:button-content>
							<em>User</em>
						</template>
						<b-dropdown-item href="#">Profile</b-dropdown-item>
						<b-dropdown-item href="#">Sign Out</b-dropdown-item>
						</b-nav-item-dropdown> -->
						<b-dropdown-item href="#">Normal Ranges</b-dropdown-item>
						<b-dropdown-item href="#">Lab Packages</b-dropdown-item>
						<b-dropdown-item href="#">Sample Kinds</b-dropdown-item>
						<b-dropdown-item href="#">Parasitology Templates</b-dropdown-item>
						<b-dropdown-item href="#">Nationality</b-dropdown-item>
						<b-dropdown-item href="#">Reject Reasons</b-dropdown-item>
						<b-dropdown-item href="#">Priority Request</b-dropdown-item>
					</b-nav-item-dropdown>
					<b-nav-item-dropdown text="Laboratory Reception">
						<b-dropdown-item href="#">Laboratory Requests</b-dropdown-item>
						<b-dropdown-item href="#">Patients Management</b-dropdown-item>
						<b-dropdown-item href="#">Sample Collection</b-dropdown-item>
						<b-dropdown-item href="#">Sample Receive</b-dropdown-item>
					</b-nav-item-dropdown>
					<!-- <b-nav-item href="#">Laboratory Results</b-nav-item> -->
					<b-nav-item-dropdown text="Laboratory Result">
						<b-dropdown-item href="#">Hematology</b-dropdown-item>
						<b-dropdown-item href="#">Clinical Chemistry Results</b-dropdown-item>
						<b-dropdown-item href="#">Hormones Results</b-dropdown-item>
						<b-dropdown-item href="#">Serology</b-dropdown-item>
						<b-dropdown-item href="#">Histopathology Results</b-dropdown-item>
						<b-dropdown-item href="#">Microbiology</b-dropdown-item>
						<b-dropdown-item href="#">Update Order Machine</b-dropdown-item>
					</b-nav-item-dropdown>
					<b-nav-item-dropdown text="Lab Views">
						<b-dropdown-item href="#">View Test Details</b-dropdown-item>
						<b-dropdown-item href="#">View Customers Price List</b-dropdown-item>
						<b-dropdown-item href="#">View Patients Laboratory Orders</b-dropdown-item>
						<b-dropdown-item href="#">View Laboratory Order Results</b-dropdown-item>
						<b-dropdown-item href="#">View Rejected Samples</b-dropdown-item>
						<b-dropdown-item href="#">View Patients Files</b-dropdown-item>
					</b-nav-item-dropdown>
					<b-nav-item-dropdown text="Reports">
						<b-dropdown-item href="#">Print Hematology Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Clinical Chemistry Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Serology Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Hormones Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Parasitology Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Microbiology Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Urine Analysis Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Semen Analysis Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Histopathology Results</b-dropdown-item>
						<b-dropdown-item href="#">Print Order Barcode</b-dropdown-item>
						<b-dropdown-item href="#">Print Laboratory Order</b-dropdown-item>
						<b-dropdown-item href="#">Print Customers Orders</b-dropdown-item>
						<b-dropdown-item href="#">Print Turn Around Time</b-dropdown-item>
						<b-dropdown-item href="#">Print Culture Result</b-dropdown-item>
						<b-dropdown-item href="#">Print OLD Result</b-dropdown-item>
					</b-nav-item-dropdown>
					<b-nav-item-dropdown text="Users">
						<b-dropdown-item href="#">Add New User</b-dropdown-item>
						<b-dropdown-item href="#">User Management</b-dropdown-item>
						<b-dropdown-item href="#">Permission Groups</b-dropdown-item>
						
					</b-nav-item-dropdown>
				</b-navbar-nav>

				<!-- Right aligned nav items -->
				<b-navbar-nav class="ml-auto">
					<b-nav-form>
					<b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
					<b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
					</b-nav-form>

					<!-- <b-nav-item-dropdown text="Lang" right>
					<b-dropdown-item href="#">EN</b-dropdown-item>
					<b-dropdown-item href="#">ES</b-dropdown-item>
					<b-dropdown-item href="#">RU</b-dropdown-item>
					<b-dropdown-item href="#">FA</b-dropdown-item>
					</b-nav-item-dropdown>

					<b-nav-item-dropdown right>
					<template v-slot:button-content>
						<em>User</em>
					</template>
					<b-dropdown-item href="#">Profile</b-dropdown-item>
					<b-dropdown-item href="#">Sign Out</b-dropdown-item>
					</b-nav-item-dropdown> -->
				</b-navbar-nav>
			</b-collapse>
		</b-navbar>
		<b-container>
			
		</b-container>
    </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.dropdown:hover .dropdown-menu {
    display: block;
    margin-top: 0;
 }
 .mainbg{
	height: 100vh;
 }
 .mainbg::before {
  content: "";
  position: absolute;
  top: 0; 
  left: 0;
  width: 100%; 
  height: 100%;  
  opacity: .2;
  background: url('./assets/imgs/bg-2.jpg');
  background-size: cover;
}
</style>
