# project01body{
    .playwrite-ie-guides-regular {
        font-family: "Playwrite IE Guides", serif;
        font-weight: 400;
        font-style: normal;
      }
      
}
.hero_image{
    background: url(sub1.jpeg)no-repeat ;
    background-size: cover;
    height: 100vh;
    position: relative;
}
h1,p,form{
    text-align: center;
}  

.hero_wrapper{
    color: white;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.hero_wrapper h1{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-align: center;
    font-size: 2.4rem;

}

.form_code .post_code{
    display: block;
    width: 80%;
    margin-left: auto;
    margin-right: auto;
    border-radius: 2rem; 
    padding: 0.5rem;
    border: none;
    text-align: center;
}

.form_code button{
    text-align: center;
    width:auto;
    border: none;
    border-radius: .3rem;
    margin-top: 1rem;
    padding: 0.2rem;
    width: 200px;
}

.product{
    width: 80%;
    margin-left: auto;
    margin-right: auto;
    
}

.product_list_item{
    float:left ;
    width: 33.33%;
}

@media screen and (max_width: 700px) {
    .product_list_item{
        width: 100%;
        float: none;
    }
}
