https://elzero.org/html-assignments-lesson-from-15-to-18/

## 01

### required
<img src="https://elzero.org/wp-content/uploads/2021/01/html-assigns-15-to-18.png">

### mine
<img src="Capture.png">

### code
```
<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <title>Table assgin</title>
        <style>
            table {
                width: 100%;
            }

        </style>
    </head>

    <body>

        <table border="1">
            <thead>
                <th>Group</th>
                <th>Avatar</th>
                <th>Name</th>
                <th>Email</th>
                <th>Character</th>
                <th>Profile</th>
            </thead>

            <tbody>
                <tr>
                    <td rowspan="2">Ninja</td>
                    <td>Hassan Eltantawy</td>
                    <td><img src="https://via.placeholder.com/70x70/f00" alt=""></td>
                    <td>test@test.test</td>
                    <td>&copy;</td>
                    <td><a href="">Profile</a></td>
                </tr>
                <tr>
                    <td>Hassan Eltantawy</td>
                    <td><img src="https://via.placeholder.com/70x70/0000FF" alt=""></td>
                    <td>test@test.test</td>
                    <td>&trade;</td>
                    <td><a href="">Profile</a></td>
                </tr>
                <tr>
                    <td>Ninja</td>
                    <td>Hassan Eltantawy</td>
                    <td><img src="https://via.placeholder.com/70x70/0000" alt=""></td>
                    <td>test@test.test</td>
                    <td>&reg;</td>
                    <td><a href="">Profile</a></td>
                </tr>
            </tbody>

            <tfoot>
                <td colspan="5">Total Members</td>
                <td>3</td>
            </tfoot>
        </table>
    </body>

</html>

```