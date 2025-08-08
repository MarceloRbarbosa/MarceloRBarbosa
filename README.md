# Marcelo Ribeiro Barbosa

 Desenvolvedor FullStack em formação na Driven Education | Curso intensivo e prático aplicando Clean Code e boas práticas de desenvolvimento 

  Estudante de Análise e Desenvolvimento de Sistemas (ADS) na UNIFRAN

---

```javascript
// marcelo.dev.js

class Desenvolvedor {
  constructor() {
    this.nome = "Marcelo Ribeiro Barbosa";
    this.status = "Em formação";
    this.curso = "Análise e Desenvolvimento de Sistemas";
    this.linguagens = ["JavaScript", "TypeScript", "HTML", "CSS"];
    this.ferramentas = ["React", "Node.js", "Express", "MongoDB", "PostgreSQL"];
    this.interesses = [
      "Boas práticas de código",
      "Arquitetura de software",
      "Desenvolvimento back-end",
      "Integração front-end"
    ];
    this.objetivo = "Construir soluções eficientes e escaláveis, aprendendo continuamente";
  }

  apresentar() {
    console.log(`Olá! Eu sou ${this.nome}, desenvolvedor em formação, pronto para criar e inovar.`);
  }
}

const marcelo = new Desenvolvedor();
marcelo.apresentar();
