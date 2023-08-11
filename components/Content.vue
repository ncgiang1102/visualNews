<template>
    <div class="main-content">
        <div class="top-post">
            <div class="list-post">
                
          
                    <ul class="post-tag">
                        <li class="post" v-for="post in posts" :key="post.id">
                            <h2>{{ post.title }}</h2>
                            <img :src="post.image" alt="Post Image">
                            <p>{{ post.category }}</p>
                        </li>
                        
                </ul>
                    
            </div>
            <div class=" main-post">

            </div>
        </div>
        <div class="last-post">

        </div>
    </div>
</template>

  
  <script>
  
  
  export default {
  
    data() {
      return {
        posts: [
          { id: 1,
            title: 'The best smart glasses to buy now, according to experts',
            image: 'https://demo.wpenjoy.com/visualnews-pro/wp-content/uploads/sites/64/2023/06/glashes.jpg',
            category: 'FASHION'
         },
          { id: 2,
             title: 'The best wrinkle-free travel clothes to pack for your summer',
             image: 'https://demo.wpenjoy.com/visualnews-pro/wp-content/uploads/sites/64/2023/06/shirt.jpg',
              category: 'FASHION' },
        { id: 3,
             title: 'World’s Best 25 Airlines for 2023 Revealed by Airline',
             image: 'https://demo.wpenjoy.com/visualnews-pro/wp-content/uploads/sites/64/2023/06/airplane-travel_J5AQI42431.jpg',
            category: 'TRAVEL' },
          
        ]

      };
    }
  }
  </script>
  

