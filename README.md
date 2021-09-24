<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
* {
    box-sizing: content-box;
}

body {
    background-color: #1a1a1a;
    counter-reset: heading;
    padding: 40px 20px;
    display: grid;
    grid-template-columns: 20% 75%;
    justify-content: space-between;
}

#nav {
    display: flex;
    height: 300px;
}

#nav ul#nav_list {
    width: 100%;
    float: left;
    box-shadow: 0px 0px 10px 1px white;
    border-radius: 8px;
    padding: 20px 24px;
    background-color: #0f0f0f;
    font-family: "Poppins";
    margin: 0 auto;
    text-align: center;
    list-style-type: none;
}

#nav ul#nav_list li {
    width: 100%;
    border-bottom: 1px solid #3d3d3d;
    border-radius: 5px;
    margin-top: 10px;
}

#nav ul#nav_list li a {
    text-decoration: none;
    color: aliceblue;
    font-weight: 700;
    font-size: 20px;
    width: 100%;
}

ul#nav_list li:hover {
    background-color: #3d3d3d;
    color: #0f0f0f;
}

#main_container {
    width: 90%;
    box-shadow: 0px 0px 10px 1px white;
    border-radius: 8px;
    padding: 20px 24px;
    background-color: #0f0f0f;
    font-family: "Poppins";
    height: 600px;
    overflow: auto;
    margin: 0 auto;
}

#profile_picture {
    border-radius: 50%;
}

h1#username {
    font-size: 80px;
    margin: 0;
    padding: 0;
    color: hsl(39, 100%, 50%);
}

h2 {
    color: aliceblue;
    font-size: 45px;
    width: 100%;
    float: left;
    text-align: left;
    margin: 10px 0px 20px 0px;
    border-bottom: 1px solid #3d3d3d;
}

h2::before {
    counter-increment: heading;
    content: counter(heading) ". ";
}

p {
    color: white;
    text-align: left;
    font-size: 22px;
}

#nav {
    display: sticky;
}

::-webkit-scrollbar {
    width: 6px;
}

::-webkit-scrollbar-track {
    background: #1a1a1a;
    border-radius: 18px;
}

::-webkit-scrollbar-thumb {
    border-radius: 18px;
    background: #3d3d3d;
}

.center {
    text-align: center;
}

.list {
    color: white;
    margin: 0;
}

details, details summary {
    padding: 0;
    margin: 0;
    display: block;
    width: 100%;
    float: left;
}

h3 {
    color: #f0eeee;
    width: 100%!important;
    float: left;
}

._logo_ {
    width: 30px;
    height: 30px;
    border-radius: 50%;
}

p.link_ a {
    color: rgb(6, 143, 255);
    text-decoration: none;
}

@media only screen and (max-width: 800px) {
    body {
        display: block;
        margin: 0;
    }
    div {
        margin: 0 auto;
        margin-bottom: 40px;
        width: 90%;
    }
    #nav {
        width: 100%;
    }
    #nav ul#nav_list {
        width: 50%;
        margin: 0 auto;
        margin-bottom: 40px;
        height: 250px;
    }
}

@media only screen and (max-width: 600px) {
    #nav {
        width: 100%;
    }
    #nav ul#nav_list {
        width: 100%;
    }
    #main_container {
        width: 80%;
    }
}
  </style>
<div id="nav">
        <ul id="nav_list">
            <li><a href="#profile_picture">Home</a></li>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#github">Github Stats</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#links">Links</a></li>
        </ul>
    </div>

    <div id="main_container">
        <div class="center"><img src="shisui1.jpg" id="profile_picture" /></div>
        <h1 id="username" class="center">Shisui</h1>
        <p class="center">Hello there 👋, I am shisui<br />Welcome to my profile page</p>

        <h2 id="introduction">Introduction </h2>
        <p>I am self taught programmer 😊, I like to develop open source projects 📖 and I also like to watch anime and
            play video games 🎮 though i suck in them.<br>I got interest in programming since my computer teacher
            flexed
            his "Hello World" skills on me 😂<br>My goal is to become something that others will want to be.</p>

        <h2 id="skills">Skills </h2>
        <p>
            As of now i am skilled in various things and they are listen below

        <h3>Programming</h3>
        <ul class="list">
            <li>JavaScript</li>
            <li>Node JS</li>
            <li>TypeScript</li>
            <li>Mongo DB</li>
            <li>React JS</li>
            <li>Html + CSS</li>
            <li>A bit Python and Java</li>
        </ul>
        <h3>Others</h3>
        <ul class="list">
            <li>Video Editing</li>
            <li>Photo Editing</li>
            <li>Server / Community Management</li>
            <li>Gaming</li>
            <li>Commentary</li>
        </ul>
        </p>

        <h2 id="github">Github Stats </h2>
        <p>
            <img
                src="https://github-readme-stats.vercel.app/api?username=KartikeSingh&show_icons=true&theme=highcontrast&count_private=true&custom_title=My Stats&include_all_commits=true">
            <img
                src="https://github-readme-stats.vercel.app/api/top-langs/?username=KartikeSingh&langs_count=69&theme=highcontrast&layout=compact">
        <h3>Github Achivements</h3>
        <img
            src="https://github-profile-trophy.vercel.app/?username=KartikeSingh&margin-h=25&column=3&theme=highcontrast">
        </p>

        <h2 id="projects">Projects </h2>
        <p>
        <h3>Open Source Projects</h3>
        <a href="https://github.com/KartikeSingh/discord-embed-builder">
            <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=KartikeSingh&repo=discord-embed-builder&theme=highcontrast">
        </a>
        <a href="https://github.com/KartikeSingh/discord-slash-command-handler">
            <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=KartikeSingh&repo=discord-slash-command-handler&theme=highcontrast">
        </a>
        <a href="https://github.com/KartikeSingh/ms-prettify">
            <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=KartikeSingh&repo=ms-prettify&theme=highcontrast">
        </a>
        <a href="https://github.com/KartikeSingh/discord-fight-game">
            <img
                src="https://github-readme-stats.vercel.app/api/pin/?username=KartikeSingh&repo=discord-fight-game&theme=highcontrast">
        </a>

        <h3>Other Projects</h3>
        <a href="https://top.gg/bot/743834886833438770"><img src="https://top.gg/api/widget/743834886833438770.svg"
                alt="Krazy bot" /></a>
        </p>

        <h2 id="links">Links </h2>
        <p class="link_">
            <a href="https://www.github.com/KartikeSingh"><img class="_logo_"
                    src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"> Github</a><br>
            <a href="https://www.npmjs.com/~shisui"><img class="_logo_"
                    src="https://cdn.discordapp.com/attachments/880732844220100608/889157100943597618/ZOXsywAAAABJRU5ErkJggg.png"> NPM</a><br>
            <a href="https://discord.gg/XYnMTQNTFh"><img class="_logo_"
                    src="https://cdn-icons-png.flaticon.com/512/906/906361.png"> Discord</a><br>
            <a href="https://twitter.com/krazy_shisui"><img class="_logo_"
                    src="https://cdn.discordapp.com/attachments/814025374123425803/889168720675635200/GP7mJZFBW9reJAAAAAElFTkSuQmCC.png">   Twitter</a>
        </p>

    </div>
