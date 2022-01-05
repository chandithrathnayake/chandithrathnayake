const QueenAmdi = require('queenamdi-public');
const Amdi = QueenAmdi.events;
require('@blackamda/queenamdi-web-api');

 Amdi.operate({pattern: 'yt', fromMe: false, dontAddCommandList: true}, (async (message, match) => {

    await message.sendMessage("please type .song for download songs 👸.");
     
}));
