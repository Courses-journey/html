https://elzero.org/html-assignments-lesson-from-24-to-27/

## 01

```
<!DOCTYPE html>
<html>

    <head>
        <meta charset="UTF-8">
        <title>Assignment</title>
    </head>

    <body>
        <form action="test.py" method="post">
            <input type="text" value="jlksfgbikdaljkgksj" hidden>
            <div>
                <label>Username</label>
                <br>
                <input type="text" required placeholder="Enter username" name="user">
            </div>
            <hr>
            <div>
                <label>Password</label>
                <br>
                <input type="password" placeholder="Write a strong password" name="pass">
            </div>
            <hr>
            <div>
                <label>Mobile</label>
                <br>
                <input type="tel" name="phone" pattern="[0-9]{5}-[0-9]{3}-[0-9]{3}"
                    placeholder="Phone number +20100 (234) 123">
            </div>
            <hr>
            <div>
                <label>Email</label>
                <br>
                <input type="email" name="email" required placeholder="Write a valid email">
            </div>
            <hr>
            <div>
                <label>Subject</label>
                <br>
                <input type="text" name="subjecy" placeholder="Enter Subject">
            </div>
            <hr>

            <input type="reset" value="Empty Form">
            <input type="submit" value="Send Data">
        </form>
    </body>

</html>

```