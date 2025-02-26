<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <style>
      .content{
    grid-template-columns: auto;
}
.gridlayout{
    display: grid;
}
.section1{
    justify-content: center;
    text-align: center;
    color: white;
    background-color: #000;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
}
.section2{
    display: flex;
    justify-content: center;
    align-content: center;
}
.work{
    justify-content: content;
    align-content: center;
}
.content-holder{
    display: flex;
    align-items: center;
    justify-content: space-between;
    align-content: center;
}
.box{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 50%;
    background-color: #D3D3D3;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 10px 10px;
    margin: 20px;
}
.separator{
    width: 1px;
    background-color: #000;
    margin: 0 20px;
    align-self: stretch;
}
.left-content{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    text-align: left;
    flex: 1;
}
.right-content{
    text-align: left;
    flex: 2;
}
.section3{
    display: flex;
    justify-content: center;
    align-content: center;
}
.section4{
    display: flex;
    justify-content: center;
    align-content: center;
}
.section5{
    display: flex;
    justify-content: center;
    align-content: center;
}
    </style>
  </head>
  <body class="content">
    <div class="gridlayout">
      <div class="section1">
        <h1>Joseph Sardina</h1>
        <h4>Web Developer</h4>
        <p>
          My name is Joseph Sardina, and I am a web developer with experience in
          both front-end and back-end development. I have worked on a variety of
          projects, ranging from user interface design to database integration.
          My focus is on creating intuitive and user-friendly websites that
          provide a seamless experience for all users, regardless of technical
          background.
        </p>
      </div>
      <div class="section2">
        <div class="work">
          <h1>My Work</h1>
        </div>
      </div>
      <div class="section3">
        <div class="box">
          <div class="content-holder">
            <div class="left-content">
              <p class="date">2024-Present</p>
              <a class="link" target="_blank" href="http://www.lisasardina.com/"
                >http://www.lisasardina.com/</a
              >
            </div>
            <div class="separator"></div>
            <div class="right-content">
              <p class="explanation">
                This website was designed and developed to promote the work of a
                new author as well as give them the ability to update the
                website on their own.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="section4">
        <div class="box">
          <div class="content-holder">
            <div class="left-content">
              <p class="date">2024-Present</p>
              <p class="link">URL here</p>
            </div>
            <div class="separator"></div>
            <div class="right-content">
              <p class="explanation">I made this website</p>
            </div>
          </div>
        </div>
      </div>
      <div class="section5">
        <div class="box">
          <div class="content-holder">
            <div class="left-content">
              <p class="date">2024-Present</p>
              <p class="link">URL here</p>
            </div>
            <div class="separator"></div>
            <div class="right-content">
              <p class="explanation">I made this website too</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
