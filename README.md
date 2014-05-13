

<html >
<head>
    <title></title>
    <style type="text/css">
        form
        {
            margin: 0 auto;
            width: 400px;
            padding: 1em;
            border: 1px solid #CCC;
            border-radius: 1em;
        }
        form div + div
        {
            margin-top: 1em;
        }
        label
        {
            display: inline-block;
            width: 90px;
            text-align: right;
        }
        input, textarea
        {
            font: 1em sans-serif;
            width: 300px;
            box-sizing: border-box;
            border: 1px solid #999;
        }
        input:focus, textbox: focus
        {
            border-color: #000;
        }
        textarea
        {
            vertical-align: top;
            height: 5em;
            resize: vertical;
        }
        button
        {
            margin-left: 7em;
        }
        .button
        {
            padding-left: 90px;
        }
    </style>
</head>
<body>
    <form action="Form1.htm" method="post">
    <div>
        <label id="lblName">
            Name:
        </label>
        <input type="text" id="txtName" />
    </div>
    <div>
        <label id="lblEmail">
            Email:</label>
        <input type="text" id="txtEmail" />
    </div>
    <div>
        <label id="lblMessage">
            Message:</label>
        <textarea id="txtMessage" rows="3" cols="3"></textarea>
    </div>
    <div>
        <button type="submit">
            Send Message</button>
    </div>
    </form>
</body>
</html>
