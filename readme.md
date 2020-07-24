 <style type="text/css">

        body {
            margin: 0;
            font-family: monospace;
            font-size: 110%;
        }

        header {
            background-color: #42cdef;
            padding: 3rem 2rem 1rem;
            text-align: center;
            color: white;
            box-shadow: lightgrey 0 0 20px;
        }

        body, header, h1, a, img {
            transition: all ease 1s;
        }

        h1:hover {
            user-select: none;
            color: #42cdef;
            text-shadow: -2px 0 white, 0 2px white, 2px 0 white, 0 -2px white;
            letter-spacing: 2px;
        }

        header img {
            border-radius: 10%;
            width: 60%;
            max-width: 15rem;
            margin: 1rem auto;
        }

        header img:hover {
            width: 130%;
            max-width: 70vw;
            border-radius: 0;
        }

        section {
            padding: 1rem 3rem;
            max-width: 50rem;
        }

        section > a {
            display: inline-block;
            text-decoration: none;
            border: #42cdef 2px solid;
            color: #42cdef;
            background-color: white;
            padding: .5rem;
            margin: .1rem;
            font-size: 120%;
        }

        a:link {
            color: #42cdef;
        }

        a:visited {
            color: #424242;
        }

        a:focus, a:hover, a:active {
            color: white;
            background-color: #42cdef;
            font-weight: bold;
        }

        a:active {
            border: #424242 2px solid;
            color: #424242;
        }

        @media (min-width: 800px) {
            body {
                font-size: 140%;
                margin-top: 3rem;
            }

            header {
                position: fixed;
                top: 0;
                height: 100%;
                width: 16rem;
            }

            section {
                padding-left: 25rem;
            }
        }
        .typed{
            display: inline-block;
        }

        .typed {
            position: relative;
            line-height: 1;
        }

        .typed:after {
            content: "";
            position: absolute;
            top:-1px;right:0;bottom:-2px;left:0;
            border-left: 2px solid #42cdef;
            background-color: white;
            animation: animatetoright 5s steps(40) infinite;
        }
		
        @keyframes animatetoright {
            0% {
                left: 0;
                margin-right: auto;
            }
			60% {
				left: 102%;
			}
            100% {
                margin-left: .6em;
                margin-right: -.6em;
            }
        }
    </style>
</head>

<body>

<header>
    <img src="https://d33wubrfki0l68.cloudfront.net/0aaaeaa1ed2303f4f23ab4e8edb0a9d55c4a3a77/e15a3/assets/avatar.jpg" alt="Profile Picture">
    <h1>Luke Storry</h1>
</header>

<section>

    <h3 class="typed">Bristol-based software developer, windsurfer & climber</h3>
    <p>I currently work at <a href="https://www.ghyston.com/">Ghyston</a>, creating and maintaining bespoke
        business-critical software.</p>
</section>

<section>
    <p>In my spare time (when I'm not out on the water, up a mountain, or curled on the sofa reading a trashy
        crime|fantasy
        novel), I enjoy using the latest technologies to build simple, performant and elegant apps|software|tools.</p>
    <ul>
        <li><strong>Current go-to stack:</strong> <a href="https://www.gatsbyjs.org/">Gatsby</a>, hosted on
            <a href="https://www.netlify.com/">Netlify</a>, with a <a href="https://firebase.google.com/">Firebase</a>
            back-end if required.
        </li>
        <li>
            <strong>Most experienced in:</strong> <a href="https://docs.microsoft.com/en-us/dotnet/csharp/">C#</a> for
            games & enterprise software, <a href="https://www.python.org/">Python</a> for machine-learning cloud
            systems, and <a href="https://reactjs.org/">React</a> for heavy-duty UIs.
        </li>
        <li>
            <strong>Learning:</strong> <a href="https://svelte.dev/">Svelte</a> for charming web-apps, <a
                href="https://www.rust-lang.org/">Rust</a> for speedy CLIs & WASM games, & <a
                href="https://expo.io/">Expo</a> for easily-deployed mobile apps.

        </li>
    </ul>
</section>

<section>
    <h3>Find me at:</h3>
    <a href="https://github.com/LukeStorry">Github</a>
    <a href="https://www.linkedin.com/in/LukeStorry">LinkedIn</a>
    <a href="https://www.twitter.com/LukeStorry/">Twitter</a>
    <a href="https://www.instagram.com/LukeStorry/">Instagram</a>
    <a href="mailto:Luke@Storry.uk">Email</a>
</section>

<section>
    <i> Feel free to check out my stuff, or contact me with your latest app idea :) </i>
</section>
