<template>
    <div class="primary-nav" >
    <div class="primary-menu ">
        <nav class="navbar ">
           
               
                <a class="nav-item" href="/">HOME</a> 
                <a class="nav-item" href="/">ADVERTISING</a> 
                
                <div class="nav-menu">
                <a class=" nav-item menu-item " href="/">BLOGGING</a>
                <ul class="dropdown-brand">
                    <li><a class="dropdown-item" href="#">SUB MENU 1</a></li>
                     <li><a class="dropdown-item" href="#">SUB MENU 2</a></li>
                    <li><a class="dropdown-item" href="#">SUB MENU 3</a></li>
                </ul>
               
                </div>
                <a class=" nav-item menu-item " href="/">BUSSINESS</a>
                <a class=" nav-item menu-item " href="/">FASHION</a>
                <a class=" nav-item menu-item " href="/">FOOD</a>
                <a class=" nav-item menu-item " href="/">LIFESTYLE</a>
                <a class=" nav-item menu-item " href="/">MARKETING</a>
                <a class=" nav-item menu-item " href="/">SEO</a>
                <a class=" nav-item menu-item " href="/">SOCIAL MEDIA</a>
                <a class=" nav-item menu-item " href="/">TECH</a>
                <a class=" nav-item menu-item " href="/">TRAVEL</a>
                <a class=" nav-item menu-item " href="/">WEB DESIGN</a>
        

            <div class="search" style="margin-left: 30px;">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                    <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                    </svg>
            </div>
        </nav>
    </div>

   

</div>
</template>

<style scoped>
@media (max-width: 760px) {

.primary-nav{
  display: none;
}

}

@media (min-width: 1200px) {
  .primary-menu{
margin-bottom: 15px;
}
.container-fluid{
    width: 1519.2px;
    height: 40.8px;
}

.navbar {
    margin: 0px 139.60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px;
}


.left-nav{
    padding:10px ;}

.nav-item{
  margin-right: 0px;
  font-weight: bolder;
  color: #f9f9f9;

  height: 20.8px;

}
.nav-item:hover{
  color: #990099;
  text-decoration: none;
}



.dropdown-brand{

  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 200px;
  font-size: 15px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  list-style: none;
}

.nav-menu:hover .dropdown-brand{
  display: block;
 
}

.dropdown-brand>li>a:hover{
  
  text-decoration: none;
  color: #990099;
}
}


</style>
