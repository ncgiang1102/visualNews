<template>
    <div class="header">
        <div class="top-bar">
         <nav class="navbar ">
                <div class="container-fluid">
                    <div class="left-nav d-flex ">
                        <a class="nav-item" href="/">About</a> 
                        <a class="nav-item" href="/">Contact</a> 
                        
                        <div class="nav-menu">
                        <a class=" nav-item menu-item " href="/">Full width Page</a>
                        <ul class="dropdown-brand">
                            <li><a class="dropdown-item" href="#">Sub Menu 1</a></li>
                             <li><a class="dropdown-item" href="#">Sub menu 2</a></li>
                            <li><a class="dropdown-item" href="#">Sub Menu 3</a></li>
                        </ul>
                       
                        </div>
                        <a class=" nav-item menu-item " href="/">Submit Article</a>
                        <a class=" nav-item menu-item " href="/">Buy Theme</a>
                    
                    </div>
                    <div class="right-nav d-flex logged ">
                           <ul class="icon">
                            <li><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
                                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
                            </svg></li>
                            <li>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
                                <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
                                </svg>
                            </li>
                            <li>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16">
                                <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z"/>
                                </svg>
                            </li>
                            <li>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                                <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/>
                                </svg>
                            </li>
                            <li>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-dribbble" viewBox="0 0 16 16">
                                <path fill-rule="evenodd" d="M8 0C3.584 0 0 3.584 0 8s3.584 8 8 8c4.408 0 8-3.584 8-8s-3.592-8-8-8zm5.284 3.688a6.802 6.802 0 0 1 1.545 4.251c-.226-.043-2.482-.503-4.755-.217-.052-.112-.096-.234-.148-.355-.139-.33-.295-.668-.451-.99 2.516-1.023 3.662-2.498 3.81-2.69zM8 1.18c1.735 0 3.323.65 4.53 1.718-.122.174-1.155 1.553-3.584 2.464-1.12-2.056-2.36-3.74-2.551-4A6.95 6.95 0 0 1 8 1.18zm-2.907.642A43.123 43.123 0 0 1 7.627 5.77c-3.193.85-6.013.833-6.317.833a6.865 6.865 0 0 1 3.783-4.78zM1.163 8.01V7.8c.295.01 3.61.053 7.02-.971.199.381.381.772.555 1.162l-.27.078c-3.522 1.137-5.396 4.243-5.553 4.504a6.817 6.817 0 0 1-1.752-4.564zM8 14.837a6.785 6.785 0 0 1-4.19-1.44c.12-.252 1.509-2.924 5.361-4.269.018-.009.026-.009.044-.017a28.246 28.246 0 0 1 1.457 5.18A6.722 6.722 0 0 1 8 14.837zm3.81-1.171c-.07-.417-.435-2.412-1.328-4.868 2.143-.338 4.017.217 4.251.295a6.774 6.774 0 0 1-2.924 4.573z"/>
                                </svg>
                            </li>
                            <li>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
                                <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"/>
                                </svg>
                            </li>

                           </ul> 
                    </div>

                 </div>
      
</nav>

        </div>
      
        <div class="site-start">
            <div class="container">
                <div class="row">
                <div class="col autho au-left" style="float: left; margin-right: 50px;">
                 <div class="" style="flex-basis: 30%;">
                        <div class="">
                            <div class="">
                                <figure class="author-image">
                                    <img decoding="async" src="https://demo.wpenjoy.com/visualnews-pro/wp-content/themes/visualnews-pro/assets/images/avatar-1.png" alt="" class="wp-image-294" width="80" height="80">
                                </figure>
                                <div class="author-content">
                                    <h2 class="" style="font-style:normal;font-weight:600">John Doe</h2>
                                    <p class="" style="font-size:12px">If you want to make your dreams come true, the first thing you have to do is wake up.</p>
                             </div>
                            </div>
                        </div>
                    </div>
                </div>

                 <div class="col autho au-center">
                    <div class="" style="flex-basis:40%">
                        <div class="">
                            <h2 style="text-decoration: none;font-style:normal;font-weight:bold;text-transform:uppercase;" class=""><a style="color:#0d0606 ;" href="https://demo.wpenjoy.com/visualnews-pro"  rel="home">VisualNews Pro</a></h2></div>
                            <p class="" style="color:#c91a1a ;margin-top:10px;margin-right:0px;margin-bottom:0px;margin-left:0px;text-transform:uppercase">WP Newspaper Theme</p>
                        </div>
                </div>
                <div class="col autho au-right" style="float: right;margin-left: 50px;">
                        <div class="" style="flex-basis: 30%;">
                                <div class="">
                                    <div class="">
                                        <figure class="author-image">
                                            <img decoding="async" src="https://demo.wpenjoy.com/visualnews-pro/wp-content/themes/visualnews-pro/assets/images/avatar-2.png" alt="" class="wp-image-295" width="80" height="80">
                                        </figure>
                                        <div class="author-content">
                                            <h2 class="" style="font-style:normal;font-weight:600">Mary Taylor</h2>
                                            <p class="" style="font-size:12px">You can have anything you want if you are willing to give up everything you have.</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                </div>
            </div>
        </div>
        </div>

        <div class="primary-nav">
            <div class="primary-menu ">
                <nav class="navbar navbar-expand-lg navbar-light bg-light">
                    <div class="container-fluid">
                        
                        <div class="left-nav d-flex ">
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
                    
                    </div>

                </div>
                    <div class="search">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                            <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                            </svg>
                    </div>
                </nav>
            </div>

           

        </div>

    </div>

</template>
<style>

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(to right, #256fc9, #7464a2 50%); /* Gradient background */
    padding: 5px 20px;
    transition: background-color 0.3s;
}
/* Đảm bảo rằng các phần tử được căn chỉnh và căn giữa dọc */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #7464a2;
    padding: 5px 20px; /* Giảm padding để thu nhỏ chiều cao */
}
/* nav left */


.nav-item{
  margin-right: 40px;
  font-weight: bolder;
  color: #f9f9f9;
  font-size:small;
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


.left-nav{
    align-items: center;
}

/* right nav */

/* Đảm bảo rằng các phần tử được căn chỉnh và căn giữa dọc */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* Hiển thị biểu tượng Twitter bên phải */
.right-nav {
    display: flex;
    align-items: center;
    margin-left: auto; /* Đẩy các biểu tượng về phía bên phải */
}

.icon {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex; /* Hiển thị các biểu tượng ngang hàng */
}

.icon li {
    color: #f9f9f9;
    margin-left: 10px; /* Khoảng cách giữa biểu tượng và các phần tử khác */
}

/* site start */
.site-start{
    margin-top: 50px;
}
.au-left .author-image {
    float: right; /* Đẩy ảnh về bên phải */
    margin-left: 20px; /* Tạo khoảng cách giữa ảnh và nội dung */
    border-radius: 50%; /* Làm cho ảnh hình tròn */
    overflow: hidden; /* Đảm bảo ảnh không bị tràn ra ngoài */
    width: 80px; /* Kích thước ảnh */
    height: 80px;
}
.au-right .author-image {
    float: left; /* Đẩy ảnh về bên phải */
    margin-right: 20px; /* Tạo khoảng cách giữa ảnh và nội dung */
    border-radius: 50%; /* Làm cho ảnh hình tròn */
    overflow: hidden; /* Đảm bảo ảnh không bị tràn ra ngoài */
    width: 80px; /* Kích thước ảnh */
    height: 80px;
}
.author-image {
    float: right; /* Đẩy ảnh về bên phải */
    margin-left: 20px; /* Tạo khoảng cách giữa ảnh và nội dung */
    border-radius: 50%; /* Làm cho ảnh hình tròn */
    overflow: hidden; /* Đảm bảo ảnh không bị tràn ra ngoài */
    width: 80px; /* Kích thước ảnh */
    height: 80px;
}


.author-content {
    overflow: hidden; /* Đảm bảo nội dung không bị tràn ra ngoài */
}

.primary-nav .primary-menu .navbar{
    background: none;
}

.primary-nav .primary-menu .nav-item{
  margin-right: 40px;
  font-weight: bolder;
  color: #170808;
  font-size:15px;
}
.nav-item:hover{
  color: #2c182c;
  text-decoration: none;
}




</style>