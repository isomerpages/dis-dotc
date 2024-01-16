---
title: Test
permalink: /join-us/permalink/
variant: markdown
description: ""
---
<style>
/\* Importing Google font - Open Sans \*/
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;600;700&display=swap');

\* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}

body {
    background: #ecececdb;
}

.card-list {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    max-width: 1250px;
    margin: 150px auto;
    padding: 20px;
    gap: 20px;
}

.card-list .card-item {
    background: #fff;
    padding: 26px;
    border-radius: 8px;
    box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.04);
    list-style: none;
    cursor: pointer;
    text-decoration: none;
    border: 2px solid transparent;
    transition: border 0.5s ease;
}

.card-list .card-item img {
    width: 100%;
		height: 100%
    aspect-ratio: 1/1;
    border-radius: 8px;
    object-fit: cover;
}

.card-list span {
    display: inline-block;
    background: #F7DFF5;
    margin-top: 32px;
    padding: 8px 15px;
    font-size: 0.75rem;
    border-radius: 50px;
    font-weight: 600;
}

.card-list .developer {
    background-color: #F7DFF5; 
    color: #B22485;
}   

.card-list .designer {
    background-color: #d1e8ff;
    color: #2968a8;
}

.card-list .editor {
    background-color: #d6f8d6; 
    color: #205c20;
}

.card-item h3 {
    color: #000;
    font-size: 1.438rem;
    margin-top: 8px;
    font-weight: 600;
}

.card-item h6 {
    color: #000;
    font-size: 1.138rem;
    margin-top: 8px;
    font-weight: 300;
}

@media (max-width: 1200px) {
    .card-list .card-item {
        padding: 15px;
    }
}

@media screen and (max-width: 980px) {
    .card-list {
        margin: 0 auto;
    }
}
	</style>
	
<div class="card-list">
        <div class="card-item">
            <img src="/images/Meet%20the%20Team/jean-tan-swe-full.png">
            <span class="developer">Developer</span>
            <h3>Jean Tan</h3>
					<h6>Turning coffee into code, one line at a time. ☕💻</h6>
        </div>
				<div class="card-item">
            <img src="/images/Meet%20the%20Team/jean-tan-swe-full.png">
            <span class="designer">Developer</span>
            <h3>Jean Tan</h3>
					<h6>Turning coffee into code, one line at a time. ☕💻</h6>
        </div>
        <a class="card-item" href="#">
            <img alt="Card Image" src="images/designer.jpg">
            <span class="designer">Designer</span>
            <h3>A "designer" is a design expert.</h3>
            <div class="arrow">
                <i class="fas fa-arrow-right card-icon"></i>
            </div>
        </a>
        <a class="card-item" href="#">
            <img alt="Card Image" src="images/editor.jpg">
            <span class="editor">Editor</span>
            <h3>An "editor" ensures content quality and accuracy.</h3>
            <div class="arrow">
                <i class="fas fa-arrow-right card-icon"></i>
            </div>
        </a>
    </div>
