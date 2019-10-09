## FizzBuzz - de 1 à 100
FizzBuzz.generate(int i) => i\
FizzBuzz.generate(1) => "1"\
FizzBuzz.generate(3) => "Fizz"\
FizzBuzz.generate(5) => "Buzz"\
FizzBuzz.generate(15) => "FizzBuzz"

## Prime Factors
PrimeFactors.generate(int n) => [n]

n => [x,...]

[ ] 2 => [2]\
[ ] 3 => [3]\
[ ] 5 => [5]\
[ ] 7 => [7]\

[ ] 4 => [2,2]\
[ ] 9 => [3,3]\
[ ] 25 => [5,5]\

[ ] 8 => [2,2,2]\
[ ] 27 => [3,3,3]\
[ ] 125 => [5,5,5]\

[ ] 3 * 5 * 7 * 3 * 3 => [3, 3, 3, 5, 7]\
