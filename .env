const express = require('express');
const app = express();
app.listen(() => console.log('ready'));
app.use('/ping', (req, res) => {
    res.send(new Date());
});
const Discord = require('discord.js');
const client = new Discord.Client();
const cmd = require('node-cmd');
const ms = require('ms');
const fs = require('fs');
const ytdl = require('ytdl-core');
const canvas = require('canvas');
const convert = require('hh-mm-ss');
const fetchVideoInfo = require('youtube-info');
const simpleytapi = require('simple-youtube-api');
const util = require('util');
const gif = require('gif-search');
const jimp = require('jimp');
const guild = require('guild');
const hastebins = require('hastebin-gen');
const getYoutubeID = require('get-youtube-id');
const pretty = require('pretty-ms');
const moment = require('moment');
const request = require('request');
const dateFormat = require('dateformat');
const prefix = "!";//برفكس بوتك

client.on('ready', async () => {
    console.log(`Logged in as ${client.user.tag}!`);
    client.user.setStatus('');
    client.user.setActivity(
        `${prefix}help`,
        { type: 'PLAYING' }
    ); 
});
///////حط اكوادك تحت 
/*تنبيه عشان تدخل ملف 
.env
سوي ملف .enn 
وادخل عليه
واحذفه وراح تكون تشوف نفسك داخل 
.env
*/







client.login(process.env.token);
