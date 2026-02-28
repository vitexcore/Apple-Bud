*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f2f2f2;
}

/* MOBILE STYLE */
@media screen and (max-width:480px){

    .header{
        background:url('bg.jpg') center/cover no-repeat;
        height:180px;
        position:relative;
    }

    .top-bar{
        position:absolute;
        bottom:-30px;
        width:100%;
        background:#f2f2f2;
        border-radius:20px 20px 0 0;
        padding:20px;
        display:flex;
        justify-content:space-between;
        align-items:center;
    }

    .top-bar h1{
        font-size:24px;
        font-weight:bold;
    }

    .back{
        font-size:22px;
    }

    .profile{
        width:40px;
        height:40px;
        border-radius:50%;
        background:#ddd;
    }

    .container{
        padding:60px 15px 20px 15px;
    }

    .card{
        background:#fff;
        border-radius:12px;
        padding:15px;
        display:flex;
        align-items:center;
        justify-content:space-between;
        margin-bottom:15px;
        box-shadow:0 3px 8px rgba(0,0,0,0.08);
    }

    .card img{
        width:60px;
        height:60px;
        object-fit:contain;
    }

    .details{
        flex:1;
        margin-left:12px;
    }

    .details h3{
        font-size:16px;
        margin-bottom:4px;
    }

    .details h4{
        font-size:14px;
        font-weight:600;
        margin-bottom:4px;
    }

    .details p{
        font-size:12px;
        color:gray;
    }

    .phone{
        font-size:20px;
        color:#f4b400;
    }
}