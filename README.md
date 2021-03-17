# Accordion-image-gallery
.......html.......
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <h1>Accordion Image Gallery</h1>

  <div class="gallery-wrap">
    <div class="item item-1"></div>
    <div class="item item-2"></div>
    <div class="item item-3"></div>
    <div class="item item-4"></div>
    <div class="item item-5"></div>
  </div>
 </div>

<div class="social">
   <i class="em em-revolving_hearts" aria-role="presentation" aria-label="REVOLVING HEARTS"></i> 
  </a>
</div>
</html>
.........css......
html, body {
  width: 100%;
  height: 100%;
}

.container {
  padding: 20px 0;
  margin: 0 auto;
  width: 1140px;
}

h1 {
  position: relative;
  margin-bottom: 45px;
  font-family: cursive;
  font-size: 44px;
  text-transform: uppercase;
  color: #800000;
}

.gallery-wrap {
  display: flex;
  flex-direction: "row-reverse";
  width: 100%;
  height: 95vh;
}

.item {
  flex: 1;
  height: 100%;
  background-position: center;
  background-size: cover;
  background-repeat: none;
  transition: flex 0.9s ease;
}
.item:hover {
  flex: 7;
}

.item-1 {
  background-image: url(http://images.fanpop.com/images/image_uploads/The-Cast-friends-144550_1021_692.jpg);
}

.item-2 {
  background-image: url(https://www.filmibeat.com/ph-big/2016/09/_14751324347.jpg);
}

.item-3 {
  background-image: url(https://i0.wp.com/www.trendingetc.com/wp-content/uploads/2021/03/The-Kissing-Booth-3.jpg?w=1000&ssl=1);
}

.item-4 {
  background-image: url(https://i.ytimg.com/vi/8olKq-lPINQ/maxresdefault.jpg);
}

.item-5 {
  background-image: url(https://cricket.yahoo.net/static-assets/waf-images/cb/15/83/6-4/pD6qcB5QDM.jpeg);
}

.social {
  position: absolute;
  right: 35px;
  bottom: 0;
}
.social img {
  display: block;
  width: 32px;
}
