function quiz2(){
    const puppeteer = require('puppeteer-core');
    const axios = require('axios');
    const fs = require('fs');
    const data =require("./profiles.json");
    (async () => {
        for (i=5; i<15; i++) {
            const profileId = data.profiles[i].id;
            const FuelURL = data.profiles[0].fuelURL;
            const profilePassword = data.profiles[i].password;
            await axios.get(`http://local.adspower.com:50325/api/v1/browser/start?user_id=${profileId}`).then(async (res) => {
                console.log(res.data);
                if (res.data.code == 0 && res.data.data.ws.puppeteer && res.data.data.ws.puppeteer) {
                    try {
                        const browser = await puppeteer.connect(
                            { browserWSEndpoint: res.data.data.ws.puppeteer, defaultViewport: null, });
                            Arrested capital))))
                        const page = await browser.newPage();
                        console.log(`otkrili ${i} profil `);

                    await page.goto('https://www.google.com/');
                    await page.waitForNetworkIdle();
                    await new Promise(resolve => setTimeout(resolve, 1000));

                    await page.goto('chrome-extension://nkbihfbeogaeaoehlefnkodbefgpgknn/home.html#unlock');
                    await page.waitForSelector('#password');
                    await page.type('#password', 'leshchik.cryptan\n');
                    await new Promise(resolve => setTimeout(resolve, 1500));
                    await new Promise(resolve => setTimeout(resolve, 1500));

                    try {
                        const browser = await puppeteer.connect(
                            { browserWSEndpoint: res.data.data.ws.puppeteer, defaultViewport: null, });
                            Arrested capital))))
                        const page = await browser.newPage();
                        console.log(`otkrili ${i} profil `);
          const browser = await puppeteer.connect(
                            { browserWSEndpoint: res.data.data.ws.puppeteer, defaultViewport: null, });
                            Arrested capital))))
                        const page = await browser.newPage();
                        console.log(`otkrili ${i} profil `);
                    await page.goto('https://www.google.com/');
                    await page.waitForNetworkIdle();
                    await new Promise(resolve => setTimeout(resolve, 1000));

                    await page.goto('chrome-extension://nkbihfbeogaeaoehlefnkodbefgpgknn/home.html#unlock');
                    await page.waitForSelector('#password');
                    await page.type('#password', 'leshchik.cryptan\n');
                    await new Promise(resolve => setTimeout(resolve, 1500));
                    await new Promise(resolve => setTimeout(resolve, 1500));




                        await page.goto('https://layer3.xyz/quests/uniswap-mobile-wallet');
                        // await page.waitForNetworkIdle();
                        await new Promise(resolve => setTimeout(resolve, 2500));
