console.log(isPrime(enter_a_number));

function isPrime(number) {
  if (number < 2) return false;
  else if (number === 2 || number === 3) return true;
  let limit = Math.floor(Math.sqrt(number));

  for (let i = 2; i <= limit; i++) {
    if (number % i === 0) {
      return false;
    }
  }
  return true;
}
