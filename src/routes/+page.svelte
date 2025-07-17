<title>Bird Quiz</title>

<style>
        body{
            background-color: azure;
        }
        img{
            width: 500px;
            margin-right: 50;
            margin-left: 20px;
            padding: 10px;
        }
        button{
            font-size: larger;
            margin-top: 0px;
            margin-bottom: 20px;
        }
        p{
            margin-left: 20px;
            font-size: large;
        }
        .heading{
            font-weight: bold;
            margin-left: 20px;
        }
        .imageBox{
            border: 1px solid blue;
            /* overflow: hidden; */
            float: left;
        }
        .answerBox{
            border: 1px solid blue;
            background-color: aliceblue;
            float: right;
            padding: 20px;
            width: fit-content;
            /* overflow: hidden; */
            /* https://stackoverflow.com/questions/1260122/expand-a-div-to-fill-the-remaining-width */
        }
</style>

<body>
    <h1 class="heading">Someday there will be a bird quiz here</h1>

    <h2 class="heading">Select the correct identification:</h2>

    <!-- <p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p> -->

    <div class="imageBox">
        <img src="img.jpg" alt="there should be an image here">

        <p style="margin-top: 0px; float: bottom">
            location: Drake Passage, <a href="https://ebird.org/profile/NDc0MjEzNw" target="_blank">https://ebird.org/profile/NDc0MjEzNw</a>
        </p> 
    </div>

    <div class="answerBox">
        <button>
            bird one
        </button>
        <br>

        <button>
            bird two
        </button>
        <br>

        <button>
            bird three
        </button>
        <br>

        <button>
            bird four
        </button>
        <br>

        <button>
            none of the above
        </button>
        <br>

        <button>
            skip this question
        </button>
    </div>

    


</body>

