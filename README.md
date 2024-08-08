# Diagrama-UML
Desafio POO.
Link para o diagrama do desafio java POO.

![UML exemplo iphone](https://github.com/user-attachments/assets/3c5c7342-1d14-48eb-9518-94344664de81)

https://mermaid.ink/img/pako:eNptksFOwzAMhl8lyqlI2wv0gDTBZQcmxBCnXrzEbS2lduUmE2zs3QlbtxWVnGLnt7_fSY7WiUdbWhdgGJ4JGoWuYpPXum-F0SyX349v2Kv4FEVf0kAOwkxhVj0ohlbeMWAtTE7mmg3ssQEvuuaIyhgvkjPazBjHii_nxiyjONDi4Rb3kIY_iSFjHQnDWF1soxI3pjtHo-405c0NH2_dAjW5-9iCU4cqdxREZI9TOOVqAn0SVST5kEPxH3A2_Z2Hn7QjfYWG-OY8aZgwPV2m28geVjsopnYSBDrAtfyKtgubfXdAPr_uGVXZ2GKHlS3z1mMNKcTKVvwrhXzx2y92toyacGFVUtPasoYw5Cj1Pk89_o4xe_oBOby8Zw?type=png)](https://mermaid.live/edit#pako:eNptksFOwzAMhl8lyqlI2wv0gDTBZQcmxBCnXrzEbS2lduUmE2zs3QlbtxWVnGLnt7_fSY7WiUdbWhdgGJ4JGoWuYpPXum-F0SyX349v2Kv4FEVf0kAOwkxhVj0ohlbeMWAtTE7mmg3ssQEvuuaIyhgvkjPazBjHii_nxiyjONDi4Rb3kIY_iSFjHQnDWF1soxI3pjtHo-405c0NH2_dAjW5-9iCU4cqdxREZI9TOOVqAn0SVST5kEPxH3A2_Z2Hn7QjfYWG-OY8aZgwPV2m28geVjsopnYSBDrAtfyKtgubfXdAPr_uGVXZ2GKHlS3z1mMNKcTKVvwrhXzx2y92toyacGFVUtPasoYw5Cj1Pk89_o4xe_oBOby8Zw)

# Codigo Markdown
classDiagram
    Iphone --|>ReprodutorMusical
    Iphone --|> AparelhoTelefonico
    Iphone --|> NavegadorInternet
    class ReprodutorMusical{

      -tocar()
      -pausar()
      -selecionarMusica(String musica)
    }
    class AparelhoTelefonico{
      -ligar(String numero)
      -atender()
      -iniciarCorreioVoz()
    }
    class NavegadorInternet{
      -exibirPagina(String url)
      -adicionarNovaAba()
      -atualizarPagina()
    }
