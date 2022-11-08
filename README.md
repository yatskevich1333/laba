<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script type="text/javascript">
        let x = 0.15324842212;
        let p =-Math.Pi;
        let code1 = 0;
        let code2 = 0;
        let code3 = 0;
        while(p<=Math.Pi)
            code1 = 1/(1 + p**2);
            code2 = Math.sqrt(Math.sqrt(1**4+(4*p**2 * 1**2))-p**2-1**2);
            code3 = 1/(p**2);
            console.log(code1 + " | " + code2 + " | " + code3 + " | " + p);
            p += x;
     </script>
   </body>
</html>
