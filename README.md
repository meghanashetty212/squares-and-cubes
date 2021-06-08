# squares-and-cubes
<!DOCTYPE html>
<html>
<head>
    <title> squares and cubes</title>
    <style>
        body{
            padding-top: 50px;
        }
        table,tr,td{

            border: solid black;
            width: 33%;
            text-align: center;
            border-collapse: collapse;
            background-color:darksalmon;

        }
        table{
           
            margin-top: 20px;

        }
    </style>
    <script>
        document.write("<center>")
        document.write("<table><tr><td colspan='3'>SQUARES AND CUBES</td></tr></table>");
        document.write("<table><tr><td>Number</td><td>square</td><td>cube</td></tr>");
        for(var n = 0; n <= 10; n++)
{
    document.write("<tr><td>" + n + "</td><td>" + n * n + "</td><td>" + n * n * n + "</td></tr>");
}
    document.write("</table></center>");
    </script>
</head>


</html>
