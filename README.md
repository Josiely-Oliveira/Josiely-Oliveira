Olá, sou Josiely Oliveira, uma estudante de Análise e Desenvolvimento de Sistemas.

- 🌱 Estudante tech com interesse em desenvolvimento web
- 🐾 Apaixonada por pets e voluntária da causa animal
- 😄 Pronomes: Ela/Dela

from PIL import Image

def mostrar_gatinho():
    # Abra a imagem do gatinho (certifique-se de que o arquivo 'gatinho.jpg' está na mesma pasta)
    try:
        gatinho = Image.open("gatinho.jpg")
        gatinho.show()
        print("Aqui está seu gatinho fofo!")
    except FileNotFoundError:
        print("Erro: Não consegui encontrar o arquivo 'gatinho.jpg'. Verifique se ele está na mesma pasta deste código.")

if __name__ == "__main__":
    mostrar_gatinho()
