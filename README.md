# JULIA
const botaoReduzirTamanho = document.getElementById("botaoReduzirTamanho");

botaoReduzirTamanho.addEventListener("click", function () {
  let letraTamanhoAtual = 1;
  document.body.style.fontSize = `${letraTamanhoAtual}rem`;
});
