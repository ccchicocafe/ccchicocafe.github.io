<!DOCTYPE html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="">
    <title>Menu 1</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/uikit.min.css" />
    <link rel="stylesheet" href="css/common.css" />
    <script src="js/uikit.min.js"></script>
    <script src="js/uikit-icons.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tabletop.js/1.6.2/tabletop.min.js"
        integrity="sha256-8za/zwqM08X55RXykMVIlHmYJXzV+4bwNzUk0MZXJoQ=" crossorigin="anonymous"></script>
</head>

<body>
    <script>
        function init() {
            Tabletop.init({
                key: 'https://docs.google.com/spreadsheets/d/e/2PACX-1vTqdYlY-saiQp8YVG5Qm3HsaWrZkH2PH1Cw5VBsBBA6hdaKuXXedvhvXvbFkWJC-zQmdh7kj3NJmOpA/pubhtml',
                    callback: function(data, tabletop) {
                        console.log(data)
                    },
                simpleSheet: true
            })
        }
        window.addEventListener('DOMContentLoaded', init)
    </script>
</body>

</html>
