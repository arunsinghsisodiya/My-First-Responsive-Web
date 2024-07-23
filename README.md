<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sofxeron</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
    margin-left: 90px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 50px;

}
ul li:hover{
    text-decoration: underline 3px #ae6454;

}

nav ul li a {
    text-decoration: none;
    color: #000;
    font-weight: bold;
}
.include{
    border: solid 3px #bd9887;
}
main {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px;
    background-color: #b23c17;
}

.content {
    display: flex;
    flex-wrap: wrap;
    max-width: 1200px;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
}

.text {
    flex: 1;
    padding: 40px;
}

.text h1 {
    font-size: 32px;
    margin-bottom: 20px;
}

.text h1 span {
    display: block;
    font-size: 36px;
    color: black;
}

.text p {
    font-size: 16px;
    line-height: 1.5;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 10px;
}

.button {
    display: inline-block;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    text-align: center;
    transition: background-color 0.3s ease;
}

.button.primary {
    background-color: #ff5722;
    color: #fff;
}

.button.primary:hover {
    background-color: #e64a19;
}

.button.secondary {
    background-color: transparent;
    color: #ff5722;
    border: 2px solid #ff5722;
}

.button.secondary:hover {
    background-color: #ff5722;
    color: #fff;
}

.image {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #b23c17;
    padding: 20px;
}

.image img {
    max-width:100%;
    height: auto;

}

@media (max-width: 768px) {
    .content {
        flex-direction: column;
    }

    .text, .image {
        flex: none;
        width: 100%;
    }

    .text {
        padding: 20px;
    }

    .image {
        padding: 10px;
    }
}

</style>
<body>
    <header>
        <div class="logo">SoftXeron</div>
        <nav>
            <ul>
                <li><a href="portfolio.html">Portfolio</a></li>
                <li><a href="startups.html">Startups</a></li>
                <li><a href="enterprises.html">Enterprises</a></li>
                <li><a href="ourprocess.html">Our Process</a></li>
                <li><a href="contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <div class="include">
    <main>
        <section class="content">
            
            <div class="text">
                <h1>A company that <span>Specialises in Strategic</span> design and technology</h1>
                <p>Lorem ipsum dolor sit amet consectetur. Id dis vitae mauris varius vel leo in sed aliquam. Aliquet eu consectetur consequat sed faucibus rhoncus pretium. Justo praesent viverra in sed tristique nunc eu risus. Condimentum lacus duis blandit pretium purus id egestas.</p>
                <div class="buttons">
                    <a href="#get-in-touch" class="button primary">Get In Touch</a>
                    <a href="#learn-more" class="button secondary">Learn More</a>
                </div>
            </div>
            <div class="text1"></div>
            <div class="image">
                <img src="https://media.istockphoto.com/id/1226886130/photo/3d-illustration-of-smiling-happy-man-with-laptop-sitting-in-armchair-cartoon-businessman.jpg?s=612x612&w=0&k=20&c=uggAty-__XRQEUPw3ex_5hehLCTLnCwbYZpoe_Cv3oQ=" alt="Person">
            </div>
        </section>
    </main>
</div>
</body>
</html>
