<div >
    <h1>Apply For Bursary</h1>
    <form>
        <label for="full name">Enter your name</label><br>
        <input type="text" style="width: 80%" id="userFName"> <br><br>
        <label for="phone">Enter your phone number</label> <br>
        <input type="tel" name="userPhone" id="userPhone" style="width: 80%"> <br> <br>
        <label for="university">Select university</label> <br>
        <select name="university" id="userUniversity" style="width: 80%;">
            <option value="NWU">North West University</option>
            <option value="UCT">University of Cape Town</option>
            <option value="UP">University of Pretoria</option>
            <option value="UJ">University of Johannesburg</option>
        </select><br> <br>
        <label for="faculty">Select Faculty</label> <br>
        <input type="text" name="userFavulty" id="userFaculty" style="width: 80%"> <br> <br>
        <label for="income">Select Family Income</label> <br>
        <input type="tel" name="userPhone" id="phone" style="width: 80%"> <br> <br>
        <input type="button" value="Submit" style="font-size: larger;">
    </form>
    
</div>

<style>
    div {
		display: flex;
		flex-direction: column;
		align-items: center;
		margin: auto auto;
        background-color: aliceblue;
        padding-bottom: 10%;
        margin-top: 30px;
        max-width: 350px;
        min-height: 200px;
        max-height: fit-content;
        
        font-family: Georgia, 'Times New Roman', Times, serif;
	}
    form {
        min-width: 90%;
        align-items: center;
        text-align: center;
        
        font-size: larger;
    
    }
    input{
        min-height: 20px;
        border-color: black;
        font-family: Georgia, 'Times New Roman', Times, serif;
    }
</style>