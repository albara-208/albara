<!-- 1 ربط ال html مع css  -->
<!-- 2 اضافة رابط  -->
<!-- 3 تعين اسم للصفحه -->
<!-- 4 اضافة رابط عليه اسمك -->
<!-- 5اضافة روابط الصفحه عند الضغط علية يوديك لي معلوماتك الشخصيه مثلا في الصفحه نفسها  -->
<!-- 6 اضافة كلام تعريفي عن نفسك وماذا تعمل واضافة زر تقوم بلضغط عليه يوصلك الى مكان مشاريعك في الصفحه نفسها واضافة روابط مواقع التواصل الاجتماعي -->
<!-- 7 اضافة الخدمات التي تقدمها انت كاالتهكير مثلا  -->
<!--7 لو عازو تضيف قوائم زياده انسخ اخر واحد والصقو وغير اسم العنوان والموضوع فقط اما استايلو بكون جاهز في ال css --> 
<!--7 font awesome اختيار الايقونات موقع-->
<!-- 8 كتابة عناصر مشاريعك  -->
 <!-- 8 لاضافة مشروع اخر اعدادات ال css جاهزة فقط انسخ البين الهاشتاج والصقو وغير العنوان والصوره والموضوع فقط  -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <!-- 2 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <!-- 1 -->
     <link rel="stylesheet" href="salv.css">
    <!-- 3 -->
    <title>albara</title>
</head>
<body>

 <header>
    <!-- 4 -->
    <a href="#" class="logo" >albara</a>
    <!-- 5 -->
    <nav class="navigation">
        <a href="#services">services</a>
        <a href="#projects">projects</a>
        <a href="#contact">contact</a>
    </nav>
</header>   

<!-- 6 -->
 <section class="main">
<div>
    <h2> HELLO, I'M ALABARA <br><span> Cyber Security</span></h2>
    <h3>I am a cyber security practitioner</h3>
    <a href="#projects" class="main-btn">viwe my work</a>

    
<div class="social-icons">
    <!-- ################################################# -->
<a href="https://www.facebook.com/profile.php?id=100005321139121" target="_blank"><i class="fa-brands fa-facebook"></i></a>
<a href="https://github.com/albara-208" target="_blank"><i class="fa-brands fa-github"></i></a>
</div>
</div>
</section>
 
<!-- 7 -->

<section class="cards" id="services">
<h2 class="title">services</h2>
<div class="content">
<div class="card">
<div class="icon">
    


  <i class="fa-solid fa-hat-cowboy"></i>

</div>
<div class="info">
<h3>Hacking</h3>
<!-- ################### -->
<!-- اضف صورة من شهادتك -->
<p> I hack harmful sites, applications and servers  </p>
</div>
</div>


<div class="card">
    <div class="icon">
   <i class="fa-solid fa-location-dot"></i> 
    </div>
    <div class="info">
    <h3>Gaps </h3>
    <!-- ################### -->
    <!-- اضف صورة من شهادتك -->
    <p>I detect vulnerabilities in websites and applications to protect them from hackers </p>
    </div>
    </div>



    <div class="card">
        <div class="icon">
     <i class="fa-solid fa-hands-holding-circle"></i>
        </div>
        <div class="info">
        <h3>Protection </h3>
        <!-- ################## -->
        <!-- اضف صورة من شهادتك -->
        <p>I protect the network and programs from hacking  </p>
        </div>
        </div>
    


</div>

</section>


<!-- 8 -->
<section class="projects" id="projects">
<h2 class="title">projects</h2>
<div class="content">


<div class="project-card">
<div class="project-image">
<img src="miges/sacyrte.png"/>
</div>
<div class="project-info">
<p class="project-category">hacking</p>
<strong class="project-title">
<span>i go too hacking</span>
<a href="https://github.com/albara-208" target="_blank" class="more-details">my hac</a>
</strong>
</div>
</div>


<div class="project-card">
    <div class="project-image">
    <img src="miges/sacyrte.png"/>
    </div>
    <div class="project-info">
    <p class="project-category">hacking</p>
    <strong class="project-title">
    <span>i go too hacking</span>
    <a href="https://github.com/albara-208" target="_blank" class="more-details">my hac</a>
    </strong>
    </div>
    </div>

<!-- ################################# -->
    <div class="project-card">
        <div class="project-image">
        <img src="miges/sacyrte.png"/>
        </div>
        <div class="project-info">
        <p class="project-category">hacking</p>
        <strong class="project-title">
        <span>i go too hacking</span>
        <a href="https://github.com/albara-208" target="_blank" class="more-details">my hac</a>
        </strong>
        </div>
        </div>


<!-- ############################# -->




</div>

</section>



<!-- لما تضغط عليه يوديك لي مكان الضغط عليو في الصفحه -->
<section class="cards contact" id="contact">

<h2 class="title">Let's work together</h2>

<div class="content">
    <div class="card">
    <div class="icon">
        
    
    
      <i class="fa-solid fa-phone"></i>
    
    </div>
    <div class="info">
    <h3>phone</h3>
    <!-- ################### -->
    <!-- اضق معلومات التواصل--->
    <p> +966570632414  </p>
    </div>
    </div>
    
    
    <div class="card">
        <div class="icon">
       <i class="fa-solid fa-envelope"></i>
        </div>
        <div class="info">
        <h3>Email</h3>
        <!-- ################### -->
        <!-- اضق معلومات التواصل--->
        <p>albraalsadq42@gmail.com</p>
        </div>
        </div>
    
    
    
    

</section>


<header class="joo" id="joo">
    <!-- 4 -->
    <a href="#" class="logo" >albara</a>
    <!-- 5 -->
    <nav class="navigation">
        <a href="#services">services</a>
        <a href="#projects">projects</a>
        <a href="#contact">contact</a>
    </nav>
</header>  

</body>
</html>


@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

*{

    font-family: "poppins", sans-serif;
    margin:0 ;
    padding:0 ;
    box-sizing: border-box;
    scroll-behavior:smooth ;
    
}

header{

background-color: rgb(203, 221, 235);
width: 100%;
/* يجعل شريط العنوان ظاهر عند التحرك في الصفحه */
position: fixed;
/* يجعل شريط العنوان ظاهر عند التنقل في الصفحه ولاشي يغطي عليه */
z-index: 999;
display: flex;
/* يفصل بين الروابط في شريط العنوان */
justify-content: space-between;
/* شريط العنوان  */
align-items: center;
/* المسافه في شريط العنوان  */
padding: 10px 200px ;

}

/* 4 */
 /* تظبيط الكلمة في شريط العنوان */
.logo{
   /* ازالة الخط تحت الكلمة */
text-decoration:none ;
color: rgb(9, 9, 240);
text-transform:uppercase ;
/* تضخيم الكلمة */
font-weight: 700;
font-size:1.8em ;

}
/* 5 */
.navigation a {
/* تظبيط روابط المعلومات  */
color: rgb(9, 9, 248);
text-decoration:none ;
font-size:1.1em ;
font: weight 500;
/* تباعد بين العناصر  */
padding-left:30px ;

}
/* تغير لون الكلمة عند التاشير عليها */
.navigation a:hover{
color: blueviolet;

}

/* تزبيط شكل عرض الملومات العامه الخاصه فيك  */
/* 6 */

section{
padding: 100px 200px ;
}

.main{
    width:100% ;
    min-height:100vh ;
    display: flex;
    /* يجعل الكلام في المنتصف تماما  */
    align-items:center ;
    /* اضافة صورة  */

     /* ###################### */
    /* اضف صورة للصفحه كامله  */
    background:url() no-repeat ;



    /* لتنسق الصورة مع مساحة الصفحه */
    background-size:cover ;
    /* تسطير الصورة  */
    background-position:center ;
    /* يخلي الصورة ثابته عند التحرك لاسفل */
    background-attachment: fixed ;
    
    }





.main h2 {

    color: aliceblue;
    font-size: 1.4em ;
    font-weight: 500 ;

}

.main h2 span{
    display:inline-block ;
    margin-top:10px ;
    color: rgb(43, 27, 224);
    font-size: 3em ;
    font-weight:600 ;

}


.main h3{

color: rgb(255, 255, 255);
font-size:2em;
font-weight:700 ;
/* المسافات بين الحروف في الكلمة */
letter-spacing:1px ;
/* طلوع الكلمة الى اعلى */
margin-top: 10px ;
/* نزول الكلمة الى اسفل */
margin-bottom: 30px ;


}
/* مواصفات الزر */
.main-btn{
color: rgb(255, 255, 255);
background-color: blue;
text-decoration:none;
font-size: 1.1em;
font-weight:600 ;
display: inline-block;
padding:0.9375em 2.1875em ;
letter-spacing:1px ;
border-radius:15px ;
margin-bottom:40px 
transition: 0.7s ease; 

}

.main-btn:hover{
    background-color: rgb(53, 60, 255);
    /* تكبير حجم ايقونة الزر عند التاشير عليها */
    transform:scale(1.1, 1.1) ;
    
    
    }

.social-icons a{
     color: aliceblue;
    font-size:1.7em ;
    padding-right:30px ;
    
}    
    
.title{
    /* يجعل الكلمة في المنتصف */
display:flex ;
justify-content:center;
color:blue;
font-size:2.2em ;
font-weight:800 ;
margin-bottom: 30px ;

}

.content{
display: flex;
justify-content:center ;
/* ترتيب القوائم جمب بعض مافوق بعض */
flex-direction:row ;
/* لو زودته قوائم تاني يتزيد بشكل جميل ومنسق */
flex-wrap:wrap ;
}

.card{
background-color: aliceblue;
width:21.25em ;
/*   وشفافية اللون الظل الرمادي حول القائمة ولونه*/
box-shadow:0 5px rgba(1 1 1 /15%) ;
border-radius:10px;
padding: 25px ;
margin:15px ; 


}

.card:hover{
transform:scale(1.1) ;
/* ماتكبر فجاة */
transition:0.7s ease ;

}


.icon{
color: rgb(0, 0, 0);
font-size:8em ;
text-align:center ;

}


.info{

text-align:center ;

}



.info h3{
color: blue;
font-size:1.2em ;
font-weight:700 ;
margin:10px ;


}



.projects{
background-color:#000016 ;

}

.projects .content{
margin-top:30px ;


}



.project-card{
background-color:#fff ;
border:3px solid #fff ;
min-height:14em ;
width:23em ;
overflow:hidden ;
border-radius:10px ;
margin: 20px ;
transition:0.7s ease ;

}


.project-card:hover .project-image{
/* ينور عند التاشير عليه */
opacity:0.9 ;

}

.project-image img{
width:100% ;


}


.project-info{
/* مساحه من يمين وفوق وتحت ويسار  */
    padding:1em ;


}

.project-category{
font-size:0.8em ;
color: black;

}

.project-title{

display: flex;
justify-content:space-between ;
text-transform:uppercase ;
font-weight:800 ;
margin-top:10px ;

}

.more-details{
    text-decoration:none ;
    color: blue;
}

.more-details:hover{

    color:rgb(25, 255, 197) ;
}

.content.info{
    font-size:4.5em ;
}

.content.info h3{
color:black ;

}

.content.info p {
font-size:1.5em ;


}


/* عشان يفتح في الجوال وباقي الاجهزة بكشل صحيح */
@media (max_width:1023px){
header{
    padding:12px 20px ;

}




.navigation a {
    padding-left:10px ;

}

.title{

    font-size:1.8em ;

}

section{
    padding:80px 20px ;

}

.main-content h2{

    font-size:1em ;
}

.main-content h3{

    font-size:1.6em ;
}


.content{

    flex-direction:column ;
    align-items:center ;
}


}


@media (max-width:641px){
    body{
        font-size:12px ;
    }

.main-content h2{

    font-size:0.8em ;
}

.main-content h3{
    font-size:1.4em ;
}


}


@media (max-width:300px){

body{
    font-size:10px ;
}


}




header joo {

    background-color: rgb(203, 221, 235);
    width: 100%;
    /* يجعل شريط العنوان ظاهر عند التحرك في الصفحه */
    position: fixed;
    /* يجعل شريط العنوان ظاهر عند التنقل في الصفحه ولاشي يغطي عليه */
    z-index: 999;
    display: flex;
    /* يفصل بين الروابط في شريط العنوان */
    justify-content: space-between;
    /* شريط العنوان  */
    align-items: center;
    /* المسافه في شريط العنوان  */
    padding: 10px 200px ;
    
    }

















