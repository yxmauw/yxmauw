## Hi there 👋 What am I busy with now? 

<a href='https://mobisoftinfotech.com/resources/blog/data-science-in-healthcare-use-cases/'><img src="https://mobisoftinfotech.com/resources/wp-content/uploads/2019/03/benefits-data-science-healthcare-blog.png" width='1000' height='200'/></a><figcaption><i>image credit: mobisoftinfotech.com</i></figcaption>

<!-- code for matrix code rain -->
var canvas = document.body.appendChild( document.createElement( 'canvas' ) ),
    context = canvas.getContext( '2d' );
context.globalCompositeOperation = 'lighter';
canvas.width = 1280;
canvas.height = 800;
draw();

var textStrip = ['胡', '怡', '碹'];

var stripCount = 60, stripX = new Array(), stripY = new Array(), dY = new Array(), stripFontSize = new Array();

for (var i = 0; i < stripCount; i++) {
    stripX[i] = Math.floor(Math.random()*1265);
    stripY[i] = -100;
    dY[i] = Math.floor(Math.random()*7)+3;
    stripFontSize[i] = Math.floor(Math.random()*16)+8;
}

var theColors = ['#cefbe4', '#81ec72', '#5cd646', '#54d13c', '#4ccc32', '#43c728'];

var elem, context, timer;

function drawStrip(x, y) {
    for (var k = 0; k <= 20; k++) {
        var randChar = textStrip[Math.floor(Math.random()*textStrip.length)];
        if (context.fillText) {
            switch (k) {
            case 0:
                context.fillStyle = theColors[0]; break;
            case 1:
                context.fillStyle = theColors[1]; break;
            case 3:
                context.fillStyle = theColors[2]; break;
            case 7:
                context.fillStyle = theColors[3]; break;
            case 13:
                context.fillStyle = theColors[4]; break;
            case 17:
                context.fillStyle = theColors[5]; break;
            }
            context.fillText(randChar, x, y);
        }
        y -= stripFontSize[k];
    }
}

function draw() {
    // clear the canvas and set the properties
    context.clearRect(0, 0, canvas.width, canvas.height);
    context.shadowOffsetX = context.shadowOffsetY = 0;
    context.shadowBlur = 8;
    context.shadowColor = '#94f475';
    
    for (var j = 0; j < stripCount; j++) {
        context.font = stripFontSize[j]+'px MatrixCode';
        context.textBaseline = 'top';
        context.textAlign = 'center';
        
        if (stripY[j] > 1358) {
            stripX[j] = Math.floor(Math.random()*canvas.width);
            stripY[j] = -100;
            dY[j] = Math.floor(Math.random()*7)+3;
            stripFontSize[j] = Math.floor(Math.random()*16)+8;
            drawStrip(stripX[j], stripY[j]);
        } else drawStrip(stripX[j], stripY[j]);
        
        stripY[j] += dY[j];
    }
  setTimeout(draw, 70);
}
<!-- code for matrix code rain -->

- 🔭 I’m currently working on ...General Assembly DSIF5 course
- 🌱 I’m currently learning ...Data Science with Python, SQL
- 👯 I’m looking to collaborate on ...Healthcare resource problems
- 🤔 I’m looking for help with ... finding a job that is family-friendly
- 💬 Ask me about ...Healthtech
- 📫 How to reach me: ...
<a href='https://www.linkedin.com/in/yxmauw/'><img align='auto' src='https://github.com/yxmauw/yxmauw/blob/main/logos/linkedin_logo.png' alt='icon | LinkedIn' width='21px'/></a> 
<a href='mailto:jewelbelle@gmail.com?subject=Love%20Your%20GitHub!'><img align='auto' src='https://github.com/yxmauw/yxmauw/blob/main/logos/gmail_logo.png' alt='icon | Gmail' width='21px'/></a>
- 😄 Pronouns: ...She/Her
- ⚡ Fun fact: ...I lived in Australia for 9.5 years

## Skills & Endorsements
I would like to add you to my professional network on the GITHUB.

* [Endorse New Skill!](https://github.com/yxmauw/yxmauw/issues/new?assignees=&labels=&template=endorsement-template.md&title=Endorse%3A+SKILL_HERE)
* [Nice Projects!](https://github.com/yxmauw/yxmauw/issues/new?assignees=&labels=&template=endorse--nice-projects-.md&title=%23%23+Project%2Fs+title+%23%23)


