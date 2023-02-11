# try-GPT-chat
const floorRotation = Math.random() >= 0.5;
const ballPosition = Math.floor(Math.random() * 100);

if (floorRotation) {
  console.log("The floor rotated! The ball stands on the floor.");
} else {
  console.log("The floor didn't rotate. The ball falls.");
  if (ballPosition <= 50) {
    console.log("The ball fell in a hole. Game over!");
  } else {
    console.log("The ball hit a platform. You win!");
  }
}

