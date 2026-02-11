function checkPassword() {
  const pwd = document.getElementById("password").value;

  if (pwd === "iamworth") {
    window.location.href = "letter.html";
  } else {
    document.getElementById("error").innerText = "Wrong password 💔";
  }
}
