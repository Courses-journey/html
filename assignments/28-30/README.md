https://elzero.org/html-assignments-lesson-from-28-to-30/

## 01-03

```
<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <title>02</title>
    </head>

    <body>
        <form method="get">
            <div>
                <label for="">Token</label>
                <br>
                <input hidden type="text" value="b92f1fc2fce391ad7af633723afd3055">
            </div>
            <br>
            <div>
                <label for="">Email</label>
                <br>
                <input type="text" value="o@o.com" readonly>
            </div>
            <br>
            <div>
                <label for="">Username</label>
                <br>
                <input autofocus required type="text" minlength="5" maxlength="20">
            </div>
            <br>
            <div>
                <h3>Skills</h3>
                <input checked id="skil01" type="checkbox" name="skils">
                <label for="skil01">Problem Solving</label>

                <input id="skil02" type="checkbox" name="skils">
                <label for="skil02">Logical Thinking</label>

                <input id="skil03" type="checkbox" name="skils">
                <label for="skil03">Advanced Search</label>

                <input id="skil04" type="checkbox" name="skils">
                <label for="skil05">Analysis</label>

                <input id="skil06" type="checkbox" name="skils">
                <label for="skil06">Planning</label>
            </div>
            <div>
                <h3>job</h3>
                <input id="job01" checked type="radio" name="job">
                <label for="job01">Front-End Developer</label>

                <input id="job02" type="radio" name="job">
                <label for="job02">Back-End Developer</label>

                <input id="job03" type="radio" name="job">
                <label for="job03">Business Analyst</label>

                <input id="job04" type="radio" name="job">
                <label for="job05">Project Manager</label>

                <input id="job06" type="radio" name="job">
                <label for="job06">Scrum Master</label>
            </div>
            <br>
            <div>
                <label for="book">Choose Book:</label>
                <select name="book" id="book">
                    <optgroup label="PHP">
                        <option value="PHPv5.0">v5.0</option>
                        <option value="PHPv7.0">v7.0</option>
                        <option value="PHPv8.0">v8.0</option>
                    </optgroup>

                    <optgroup label="Python">
                        <option value="Pythonv2.0">v2.0</option>
                        <option value="Pythonv3.0">v3.0</option>
                        <option value="Pythonv3.9">v3.9</option>
                    </optgroup>
                </select>
            </div>
            <br>
            <textarea name="question" id="" cols="30" rows="10"
                placeholder="Write here why you want to learn programming!"></textarea>
            <br>
            <input type="reset" value="Empty">
            <input type="submit" value="Send">
        </form>
    </body>

</html>

```