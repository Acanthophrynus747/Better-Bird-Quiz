<style>
    body{
        background-color: azure;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
    button{
        margin-top: 0px;
        margin-bottom: 0px;
    }
    p{
        margin-left: 20px;
        font-size: large;
    }
    h1{
        font-weight: bold;
        margin-left: 20px;
    }
    .imageOne{
        width: 750px;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
    .explainBox{
        text-align: left;
        font-size: large;
        border: 0px;
        width: 750px;
        margin: auto;
        padding: 10px;
    }
    .startButton{
        text-align: center;
        padding: 5px;
        font-size: larger;
    }
    .formBox{
        text-align: left;
        background-color: aliceblue;
        border: 1px dashed black;
        width: 750px;
        margin: auto;
        padding: 10px;
    }
    .formWrapper{
        text-align: left;
        font-size: large;
    }
    table, td{
        border: 1px;
        font-size: large;
        /* th is header
        td is table data, everything between is content of a table cell
        tr is table row*/
    }
</style>

<title>Bird Quiz</title>

<body>
    <h1 style="text-align: center">Customizable Bird ID Quiz</h1>

    <h2 style= "text-align: center; font-weight: bold">
        Welcome!
    </h2>

    <img src="cormorant.jpg" alt="cormorant" class="imageOne">

    <h3 style="text-align: center">
        Create your own customized bird identification photo quiz:
    </h3>

    <div class="formBox">
        <form action="/something.php" class="formWrapper">
            <table>
                <tr>
                    <td><label for="region">Choose an eBird region (county, state, province, country, or even high seas):</label></td>
                    <td><input type="text" id="region" name="region"></td>
                </tr>
                <tr>
                    <td><label for="time_of_year">Choose a day of the year:</label></td>
                    <td><input type="text" id="time_of_year" name="time_of_year"></td>   
                </tr>
                <tr>
                    <td><label for="taxa_included">Choose which bird taxa to include in your quiz (optional):</label></td>
                    <td><input type="text" id="taxa_included" name="taxa_included"></td>
                </tr>
                <tr>
                    <td><label for="taxa_excluded">Choose which bird taxa to exclude from your quiz:</label></td>
                    <td><input type="text" id="taxa_excluded" name="taxa_excluded"></td>
                </tr>
            </table>
        </form>

        <div class="startButton">
            <button>Begin Quiz</button>
        </div>
    </div>

    <div class = "explainBox">
        <p>
            eBird's bird identification quiz feature is an invaluable tool for improving one's bird identification ability, especially when reviewing the expected species for a region. 
            However, eBird currently provides no ability to quiz identification within one specific taxon or group. 
            This can be inconvenient when, for instance, one wants to only study gulls from a particular region.
            Thus, we have utilized the Cornell Lab of Ornitholgy's eBird API to create a bird ID quiz that is customizable by taxonomy.
            etc etc. 
        </p>
    </div>
</body>



