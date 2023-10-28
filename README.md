<style>
    .clearfix::after {
        content: "";
        display: block;
        clear: both;
    }

    h1.title {
        text-align: center;
        font-size: 48px;
        font-weight: bold;
    }

    main .introduction {
        float: left;
        width: 45%;
        font-size: 18px;
        margin-right: 5%;
    }

    main .github-stats {
        float: right;
        width: 50%;
        text-align: center;
        border-left: 2px solid #333;
        box-sizing: border-box;
    }

    main .github-stats h3 {
        font-size: 20px;
    }

    .languages-tools {
        margin-top: 10%;
    }

    .languages-tools h3 {
        font-size: 30px;
        text-align: center;
        margin-bottom: 4%;
    }

    .languages-tools h4 {
        text-align: center;
        font-size: 22px;
        text-decoration: underline;
    }

    .languages .language {
        float: left;
        width: 32%;
        margin-right: 2%;
    }

    .languages .language:last-child {
        margin-right: 0;
    }

    .languages .language img {
        width: 100%;
        height: 200px;
        object-fit: scale-down;
        text-align: center;
    }

    .tools .tool {
        float: left;
        width: 18%;
        margin-right: 2.5%;
    }

    .tools .tool:last-child {
        margin-right: 0;
    }

    .tools .tool img {
        width: 100%;
        height: 200px;
        text-align: center;
        object-position: center center;
        object-fit: scale-down;
        margin-right: 2%;
    }
</style>
<h1 class="title">
    Pendevx
</h1>
<main>
    <div class="clearfix">
        <div class="introduction">
            <h3>About me</h3>
            <p>
            Hello there, my name is Guangheng Xian, and I am a student software developer at Auckland University of Technology!
            </p>
        </div>
        <div class="github-stats">
            <h3>
                Github Statistics
            </h3>
            <img src="https://raw.githubusercontent.com/pendevx/github-stats-transparent/output/generated/overview.svg">
        </div>
    </div>
    <div class="languages-tools">
        <h3>Languages and Tools</h3>
        <div class="languages clearfix">
            <h4>Languages</h4>
            <div data-csharp class="language">
                <img src="https://user-images.githubusercontent.com/29004603/75462714-9dd79b80-59bf-11ea-8e6b-575765733340.png">
            </div>
            <div data-js class="language">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/768px-JavaScript-logo.png">
            </div>
            <div data-java class="language">
                <img src="https://1000logos.net/wp-content/uploads/2020/09/Java-Logo.png">
            </div>
        </div>
        <div class="tools clearfix">
            <h4>Tools and Frameworks</h4>
            <div data-reactjs class="tool">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1150px-React-icon.svg.png">
            </div>
            <div data-nextjs class="tool">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Nextjs-logo.svg/2560px-Nextjs-logo.svg.png">
            </div>
            <div data-aws class="tool">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/2560px-Amazon_Web_Services_Logo.svg.png">
            </div>
            <div data-git class="tool">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/512px-Git-logo.svg.png?20160811101906">
            </div>
            <div data-dotnet class="tool">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Microsoft_.NET_logo.svg/2048px-Microsoft_.NET_logo.svg.png">
            </div>
        </div>
    </div>
</main>
