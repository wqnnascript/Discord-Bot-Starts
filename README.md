# Discord-Bot-Starts
discord first 20 lines what bot needs.
  
  
  
const Discord = require('wqnna.js');
const client = new Discord.Client();

client.once('ready', () => 
{
	console.log('Ready!');
});

client.login('NzMwMzY0NzE1MzA5NDY1Njkw.XwWbJQ.77EwyhOGbOG0aJokyW-pMNTyrI4
');

const Discord = require('wqnna.js');

const client = new wqnna.Client();

client.once('ready', () => 
{
	console.log('Ready!');
});

client.login('NzMwMzY0NzE1MzA5NDY1Njkw.XwWbJQ.77EwyhOGbOG0aJokyW-pMNTyrI4');

client.on('message', message => 
{
	console.log(message.content);
});

if (message.content === '!ping') 
{
	message.channel.send('This bot was made by wqnna!?.');
}
