# Cartão digital NFC

**Abrir:** https://alfero1968.github.io/cartao/

Cada participante cria o próprio cartão (nome, posicionamento, WhatsApp e redes). A página gera um link para gravar numa tag NFC (NTAG215) e um QR code de reserva. Os dados ficam no próprio link, sem servidor e sem banco de dados.

- **Android com Chrome:** o botão "Gravar na tag agora" grava direto pela página.
- **iPhone e outros celulares:** copie o link e grave com o app NFC Tools (Escrever → Adicionar registro → URL).
- Quem encosta o celular na tag vê o cartão e pode chamar no WhatsApp, salvar o contato ou abrir as redes.

Arquivos:
- `index.html`: o cartão inteiro. O nome do evento fica na constante `EVENTO`.
- `qrcode.js`: gerador de QR code (MIT, Kazuhiko Arase).
- `qr-telao.png` e `qr-cartao.png`: QR codes que levam para esta página.
