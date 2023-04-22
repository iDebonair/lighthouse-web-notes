const whatToDoForLunch = (hungry, availableTime) => {
  if (!hungry) {
    console.log("You're not hungry. Get back to work!");
  } else if (hungry && availableTime < 20) {
    console.log("You're hungry but don't have much time. You could pickup something at MacDonalds and eat it at the lab");
  } else if (hungry && availableTime >= 20 && availableTime < 30) {
    console.log("You're hungry and have some time. You can try Tim Hortons nearby");
  } else if (hungry && availableTime >= 30) {
    console.log("You're hungry but you should reconsider how much time you actually have to spare");
  }
};
(whatToDoForLunch(true,20));