<template>
    <div class="book-wrapper" >

    <button class="go-back-btn"></button>
    <div class="book-content">
    <img src="" alt="">
    <div book-info>
    <h1>Book title</h1>
    <h2>Second title</h2>
    <p>Description Lorem ipsum dolor sit amet consectetur, adipisicing elit.
     Possimus nemo voluptatibus iste corporis omnis deleniti a perspiciatis nam illo quidem illum fuga enim, deserunt qui rerum obcaecati placeat et doloribus?</p>

    <section class="bookinfos">
    <p>Audience:</p>
    <p>First published:</p>
    <p>Pages</p>
    <p>Publisher</p>
    </section>

    <button class="add-to-cart">Oh, i wanna read it!</button>
    </div>
    </div>
    </div>
</template>

<style scoped>
.book-wrapper{
    backgroundcolor:rgb(54, 54, 54);
    padding-left: 20rem;
    padding-top: 10rem;

}
.go-back-btn{
border-radius: 50%;
background-color:white ;
color: white;
height: 30px;
}
.book-info{
    display: grid;
    width: 75vw;

}
.add-to-cart{
    background-color: white;
    color: rgb(54, 54, 54);
}
.bookinfos{
    display: grid; 
    grid-template-columns: repeat(2, 1fr);
}
h1{
    font-size: 48px;
}
h2{
    font-size: 38px;
    font-weight: 100;
}


</style>