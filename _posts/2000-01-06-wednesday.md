---
title: 'ScoreBoard'
bg: wednesday
color: white
border-color: thursday
fa-icon: bar-chart
---


<!-- 🏁 | Mentee | Project | Score |
🥇 | Arun Bhagat | Image Captioning |  321  |
🥈 | Rajiv Ranjan Singh | Livestream, Image Captioning, A-POP, iBlog |  259  |
🥉 | Swarnima Tiwari | Covid Cure |  153  |
💯 | Harit Yadav | Emotion Recog | 139.5 |
💯 | Aitik | Emotion Recog | 138.5 |
💯 | Md. Zeeshan Equbal | A-Pop |  123  |
✔️ | Animesh | Emotion Recog | 89.5  |
✔️ | Ayush Nanda | iBlog | 45 |
✔️ | Vaibhav | Emotion Recog | 44.5  |
✔️ | Asra | Emotion Recog | 44.5  |
✔️ | Shivam | Emotion Recog | 44.5  |
✔️ | Vidit Chopra | A-Pop |  28   | -->

<style>
  .blue { color: #185875; }
  .yellow { color: #FFF842; }

table {
  text-align: left;
}

td {
	  font-weight: normal;
	  font: 2em;
    -webkit-box-shadow: 0 2px 2px -2px #0E1119;
    -moz-box-shadow: 0 2px 2px -2px #0E1119;
    box-shadow: 0 2px 2px -2px #0E1119;
}

  td {
	  padding-bottom: 2%;
	  padding-top: 2%;
  padding-left:2%;  
}


  td:first-child { color: #347e26; }

  tr:hover {
    background-color: #464A52;
    -webkit-box-shadow: 0 6px 6px -6px #0E1119;
    -moz-box-shadow: 0 6px 6px -6px #0E1119;
    box-shadow: 0 6px 6px -6px #0E1119;
  }

td:hover {
  background-color: #666;
  color: #fff;
  font-weight: bold;
  
  box-shadow: #222 -1px 1px, #222 -2px 2px, #222 -3px 3px, #222 -4px 4px, #222 -5px 5px, #222 -6px 6px;
  transform: translate3d(6px, -6px, 0);
  
  transition-delay: 0s;
	  transition-duration: 0.4s;
	  transition-property: all;
  transition-timing-function: line;
}

@media (max-width: 800px) {
  td:nth-child(3),
  th:nth-child(3) { display: none; }
}

table {
	background: #f5f5f5;
	border-collapse: separate;
	box-shadow: inset 0 1px 0 #aaa;
	font-size: medium;
	line-height: 24px;
	margin: 30px auto;
	text-align: left;
}	

th {
	background:linear-gradient(#777, #444);
	border-left: 1px solid #555;
	border-right: 1px solid #777;
	border-top: 1px solid #555;
	border-bottom: 1px solid #333;
	box-shadow: inset 0 1px 0 #999;
	color: #fff;
	padding: 10px 15px;
	position: relative;
	text-shadow: 0 1px 0 #000;	
}

th:after {
	background: linear-gradient(rgba(255,255,255,0), rgba(255,255,255,.08));
	content: '';
	display: block;
	height: 25%;
	left: 0;
	margin: 1px 0 0 0;
	position: absolute;
	top: 25%;
	width: 100%;
}

th:first-child {
	border-left: 1px solid #777;	
	box-shadow: inset 1px 1px 0 #999;
}

th:last-child {
	box-shadow: inset -1px 1px 0 #999;
}

th h5{
  font-family: monospace;
  font-size:larger;
  font: bolder;
  text-align: center;
}

td {
	border-right: 1px solid #fff;
	border-left: 1px solid #e8e8e8;
	border-top: 1px solid #fff;
	border-bottom: 1px solid #e8e8e8;
	padding: 10px 15px;
	position: relative;
	transition: all 300ms;
}

td:first-child {
	box-shadow: inset 1px 0 0 #fff;
}	

td:last-child {
	border-right: 1px solid #e8e8e8;
	box-shadow: inset -1px 0 0 #fff;
}	


tr:nth-child(odd) td {
	background-color: #111;	
}
tr:nth-child(even) td {
	background-color: #000;	
}

tr:last-of-type td {
	box-shadow: inset 0 -1px 0 #fff; 
}

tr:last-of-type td:first-child {
	box-shadow: inset 1px -1px 0 #fff;
}	

tr:last-of-type td:last-child {
	box-shadow: inset -1px -1px 0 #fff;
}	

tbody:hover td {
	color: transparent;
	text-shadow: 0 0 3px #aaa;
}

tbody:hover tr:hover td {
  color: white;
	text-shadow: 0 0 2px #222;
}

tr:hover tr{
  font: larger;
}

td:hover td {
  font: bolder;
}

</style>


<table>
  <tbody>
    <tr>
      <th><h5>🏁</h5></th>
      <th><h5>Mentee</h5></th>
      <th><h5>Project</h5></th>
      <th><h5>Score</h5></th>
    </tr>
    <tr>
      <td>🥇</td>
      <td>Arun Bhagat</td>
      <td>Image Captioning</td>
      <td>321</td>
    </tr>
    <tr>
      <td>🥈</td>
      <td>Rajiv Ranjan Singh</td>
      <td>Livestream, Image Captioning, A-POP, iBlog</td>
      <td>259</td>
    </tr>
    <tr>
      <td>🥉</td>
      <td>Swarnima Tiwari</td>
      <td>Covid Cure</td>
      <td>153</td>
    </tr>
    <tr>
      <td>💯</td>
      <td>Harit Yadav</td>
      <td>Emotion Recog</td>
      <td>139.5</td>
    </tr>
    <tr>
      <td>💯</td>
      <td>Aitik</td>
      <td>Emotion Recog</td>
      <td>138.5</td>
    </tr>
    <tr>
      <td>💯</td>
      <td>Md. Zeeshan Equbal</td>
      <td>A-Pop</td>
      <td>123</td>
    </tr>
    <tr>
      <td>✔️</td>
      <td>Animesh</td>
      <td>Emotion Recog</td>
      <td>89.5</td>
    </tr>
    <tr>
      <td>✔️</td>
      <td>Ayush Nanda</td>
      <td>iBlog</td>
      <td>45</td>
    </tr>
    <tr>
      <td>✔️</td>
      <td>Vaibhav</td>
      <td>Emotion Recog</td>
      <td>44.5</td>
    </tr>
    <tr>
      <td>✔️</td>
      <td>Asra</td>
      <td>Emotion Recog</td>
      <td>44.5</td>
    </tr>
    <tr>
      <td>✔️</td>
      <td>Shivam</td>
      <td>Emotion Recog</td>
      <td>44.5</td>
    </tr>
    <tr>
      <td>✔️</td>
      <td>Vidit Chopra</td>
      <td>A-Pop</td>
      <td>28</td>
    </tr>
  </tbody>
</table>
