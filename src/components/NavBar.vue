<template>
  <header class="navbar">
        
        <section class="head-nav">
          f
        </section>
        <section class="mid-nav">
            <article class="icon-area">
              <img src="" alt="icon" class="header-icon">

            </article>
            <article class="mid-area">
              <form action="" class="search-bar">

                <input type="text" class="search-ipt"/>
                <button class="search-ico">lukl</button>

              </form>
            </article>
            <article class="user-actions">
                <div class="contact">
                  <span class="material-icons">forum</span>
                    <p>Atendimento</p>
                </div>
                <div class="account">
    
                  <span class="material-icons">account_circle</span>
                  
                  
                  <p>Minha Conta</p>
                </div>
      
            </article>
           
        </section>
        
        <nav>
          <ul>
            
          </ul>
        </nav>
        


  </header>
</template>


<script>


export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<style scoped>

   header.navbar {
        min-width: 100vw;
        height: 180px;

        background-color: #1c1c21;
    }

     section.mid-nav {
      height: 100px;
     
      display: flex;
      align-items: center;
      justify-content: center;
     
    }


    section.head-nav {
      height: 24px;
      
    }

   article.icon-area {
     
      flex-grow: 1;
      height: 100%;
   }

   article.mid-area {
   
      flex-grow: 2;
      display: flex;
      justify-content: center;
   }

   article.user-actions {
    
     flex-grow: 1;
     display: flex;

     height: 100%;
     justify-content: center;
     align-items: center;
   }

   article.user-actions .contact, .account {

    
    
     font-size: 0.7rem;
     color: #fff;
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
     padding: 3px;
     cursor: pointer;

  

   }

   article.user-actions .contact {
     margin-right: 15px;
   }

   article.user-actions p {
     font-weight: bold;
     font-size: 12px;
     margin-top: 8px;
   }


    

   

    .search-bar {
 
      display: flex;
      justify-content: center;
      background-color: #fff;
      width: 750px;
      
      height: 45px;
    }

   

    .search-ipt {
      background: transparent;
      border: none;
      width: 90%;
      font-size: 1em;
      padding: 10px;
      
    }

    button.search-ico {
      width: 10%;
      border: none;
      background: transparent;

    
    }


</style>