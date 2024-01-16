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

.card-list {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    max-width: 1250px;
    padding: 20px;
    gap: 20px;
}

.card-list .card-item {
    background: #fff;
    padding: 26px;
    border-radius: 8px;
    box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.04);
    list-style: none;
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

.card-list-horizontal {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    max-width: 1250px;
    padding: 20px;
    gap: 20px;
}
	
.card-list .card-item-horizontal {
    background: #fff;
    padding: 8px;
    border-radius: 8px;
    box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.04);
    list-style: none;
    text-decoration: none;
    border: 2px solid transparent;
    transition: border 0.5s ease;
}
	
.card-list-horizontal .card-item-horizontal img {
    width: 80%;
		height: 80%
    aspect-ratio: 1/1;
    border-radius: 8px;
    object-fit: cover;
}
	
.card-list-horizontal span {
    display: inline-block;
    background: #F7DF34;
    margin-top: 16px;
    padding: 8px 15px;
    font-size: 0.75rem;
    border-radius: 50px;
    font-weight: 600;
}

.card-list-horizontal .hddotc {
    background-color: #FBDAB9;
    color: #593616;
}	
	
.card-item-horizontal h3 {
    color: #000;
    font-size: 1.438rem;
    margin-top: 8px;
    font-weight: 600;
}

.card-item-horizontal h6 {
    color: #000;
    font-size: 1.138rem;
    margin-top: 8px;
    font-weight: 300;
}
	
.card-list .lead {
    background-color: #FAFBC4;
    color: #60601C;
}

.card-list .swe {
    background-color: #d1e8ff;
    color: #2968a8;
}

.card-list .designer {
    background-color: #F7DFF5; 
    color: #B22485;
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
	
<div>
<div class="card-list-horizontal">
        <div class="card-item-horizontal">
            <img src="/images/Meet%20the%20Team/david-kok.png">
        </div>
	<div class="card-item-horizontal">
          <span class="hddotc">Head DOTC</span>
		      <h3>David Kok</h3>
					<h6>"People solve problems. Good people solve problems well. Problems train people. Good problems train people well. <br><br>At DOTC, we believe that if necessity is the mother of invention, the space to experiment without fear is the father."</h6>
	</div>
	</div>
<div>
	<hr style="width:100%;border-top: 1px solid #000;margin-top:20px;margin-bottom:20px;margin-left:16px;margin-right:16px">
</div>

<header style="font-size:50px;margin:16px;color:Dodgerblue">Product Team</header>
</div>
	
<div class="card-list">
        <div class="card-item">
            <img src="/images/Meet%20the%20Team/jean-tan-swe-full.png">
            <span class="lead">SWE Team Lead</span>
            <h3>Jean Tan</h3>
					<h6>Turning coffee into code, one line at a time. ☕💻</h6>
        </div>
				<div class="card-item">
            <img src="/images/Meet%20the%20Team/jean-tan-swe-full.png">
            <span class="swe">Developer</span>
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
