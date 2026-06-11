🌸 PAULOZINXZ_YT 🌸
Base leve, organizada e fácil — ideal para iniciantes.
 
🚀 LIGAR:
• QR Code → sh start.sh
• Código de emparelhamento → sh start.sh cod
 
⚙️ CONFIG (database/config.json):
• NumeroDoDono: seu número (ex: 5592...)
• prefix: símbolo dos comandos (ex: !)
• NomeDoBot: nome do bot
 
📂 PLUGINS (carregamento automático):
Pastas:
admin/ → só admins | dono/ → só você | premium/ → usuários premium | cmds-aleatorios/ → público
 
Estrutura do comando (.js):
module.exports = {
name: 'nome',
description: 'o que faz',
category: 'categoria',
aliases: ['apelido'],
async execute({ reply }) { reply('mensagem') }
}
 
📊 MENU:
!rmcmd nome → esconder | !rncmd nome → mostrar
 
❄️ EXTRAS:
Auto-reload, boas-vindas automático, compatível com novos IDs
 
🛠️ INSTALAR:
npm install --legacy-peer-deps
 
🌸 Criador: PAULOZINXZ_YT — Mantenha os créditos