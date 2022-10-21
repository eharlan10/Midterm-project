# Below is my code for the HTML FizzBuzz challenge.

<title>Fizz Buzz</title> <script>
function fizzbuzz() { var display = document.getElementById('display'); var displayHTML = ""; for (i = 0; i < 101; i++) { if (i % 15 == 0) displayHTML += "

" + "Fizzbuzz" + "

"; else if (i % 3 == 0) displayHTML += "
" + "Fizz" + "

"; else if (i % 5 == 0) displayHTML += "
" + "Buzz" + "

"; else displayHTML += "
" + i + "

"; } display.innerHTML = displayHTML }
</script>
