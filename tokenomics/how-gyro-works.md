---
description: Tokenomics
---

# Paano gumana ang GYRO

**Paano gumana ang Gyro:**

Bawat GYRO token ay sinusuportahan ng 1 USD (i.e. USDT, DAI, BUSD, USDC) sa treasury.&#x20;

Magsisimula kami sa USDT bilang aming treasury asset. Pagkatapos ng paglulunsad, magdaragdag kami ng iba pang mga stablecoin para balansehin ang aming treasury. Kabilang dito ang DAI, BUSD, USDC atbp.&#x20;

Ang mga token ay hindi maaaring i-mint o sinusunog ng sinuman maliban sa protocol.&#x20;

Ang protocol ay mint o nasusunog lamang bilang tugon sa presyo.&#x20;

Hindi nagre-rebase ang GYRO. Sa halip, ang isang bagong supply ay nilikha sa pamamagitan ng direktang pagbebenta sa merkado at sinusunog sa pamamagitan ng mga direktang pagbili mula sa merkado. Sa ganitong paraan, ang GYRO ay nananatiling suportado ng mga tunay na asset sa treasury, ibig sabihin, USD.

Ang mga ito ay karaniwang isinasalin sa:

Kapag nagtrade ang GYRO na mas mababa sa 1 USDT, bibilhin ito ulit ng protocol at susunugin ang GYRO.

Kapag nagtrade ang GYRO na mas mababa sa 1 USDT, ang protocol ay magmi-mints at magbebenta ng bagong GYRO.

Ito ay dahil ang treasury ay dapat magkaroon ng 1 USDT at 1 USDT lamang para sa bawat GYRO tuwing ito ay binili o ibebenta kaya ito ay kumikita. Nangangahulugan na ang protocol ay makakakuha ng higit sa 1 USDT para sa bahagi ng pagbebenta o gumastos ng mas mababa sa 1 USDT sa bahagi ng pagbili.

Ang katotohanan na ang protocol ay may hawak na USDT para sa bawat token ay nagbibigay-daan sa amin na sabihin nang may katiyakan na ang GYRO ay hindi magbe-trade sa ibaba ng intrinsic na halaga nito sa mahabang panahon.

Ang mga pamumuhunan ay maaaring gawin nang may tinukoy na panganib dahil 1 USDT ang garantisadong pangmatagalang palapag ng presyo. At dahil dito, ang protocol ay maaaring (at bibili) nang walang katiyakan na mas mababa ng 1 USDT hanggang sa walang matitirang nagbebenta, kahit na ang supply ay nabawasan sa 0. Sa halimbawang ito, ang kaganapang ito ay magbibigay ng gantimpala sa mga hindi nagbebenta nang labis dahil sila ay mapupunta sa isang tipak ng bawat token na nasunog!

Ang paghawak ng mga stablecoin sa likod ng mga token ay lumilikha din ng pagkakataon sa pagbuo ng ani.

Ang pag-lock ng mga stablecoin sa isang vault ay magiging isang basura. Dahil ang protocol ay hindi kailanman nangangailangan ng higit sa ilang porsyento ng mga reserba, kahit na sa magkaroon ng down days, ay nangangahulugang malaya kang gamitin ang natitira upang isaksak sa mga yield aggregator at idagdag ang mga nalikom na iyon sa mga kita mula sa pagbili at pagbebenta ng GYRO.

Ang unang pamamahagi ng tubo ng Gyro

90% para sa mga staker

10% sa desentralisadong autonomous na organisasyon o DAO (ang mga alokasyong ito ay babaguhin, kung kinakailangan, ayon sa pagpapasya ng DAO).

Ang lahat ng mga reward ay binabayaran sa GYRO na sinusuportahan ng mga stablecoin.

Ang sistemang ito ay nagpapanatili ng isang matatag na intrinsic na halaga at binabawasan ang insentibo na papel ng pagpapahalaga sa pabor ng akumulasyon. Tulad ng totoong pera, sinusubukan mong makaipon ng mas maraming dolyar at hindi mo kailangang hilingin sa isang bituin na ang iyong mga dolyar ay maging mas nagkakahalaga. Bagama't parehong maaaring mangyari.

**Staking and Rebasing**&#x20;

Ang protocol ay namamahagi ng mga token sa pamamagitan ng pagpapadala sa kanila sa staking contract nang hindi humihingi ng sGYRO pabalik. Pinapataas nito ang ratio ng GYRO staked sa sGYRO outstanding, at nagreresulta sa rebase para itama ang pagkakaiba.&#x20;

Halimbawa mayroong 500k GYRO staked at 500k sGYRO outstanding. Ang protocol ay gumawa ng $5k na tubo para sa araw, na ginagamit nito upang i-mint at ibalik ang 5k GYRO. Ipinapadala nito ang mga GYRO sa kontrata ng staking; mayroon na ngayong 505k GYRO staked at 500k sGYRO outstanding. Kailangang tumaas ng 5k, o 1%, ang supply ng sGYRO, para bumalik sa balanse. Kaya, ang sGYRO ay muling binase ng 1%.&#x20;

Ang tanging caveat ay ang mga rebase ay nangyayari nang retroactive. Ang pagtatapos ng epoch 100 ay nagti-trigger ng rebase ng mga kita mula sa epoch 99. Ang pagkaantala na ito ay nagbibigay-daan sa iyong makita kung ano ang nawawala sa iyo kung gusto mong i-unstake o kung ano ang makukuha mo kung gusto mong ipusta.&#x20;

Ang staking ay kung paano namin ibinabahagi ang mga kita nang pantay-pantay sa mga kalahok. Sa pamamagitan ng sGYRO, lahat ay tumatanggap ng parehong porsyento ng kita sa bawat panahon. Ang rebasing ay nagpapahintulot din sa amin na pagsamahin ang ani nang hindi na kailangang mag-ani o gumawa ng anuman maliban sa paghawak.

**Bonding**&#x20;

Ang bonding ay ang proseso ng pangangalakal ng LP share sa protocol para sa GYRO. Ang protocol ay sumipi ng isang halaga ng GYRO at isang panahon ng vesting para sa kalakalan. Mahalagang malaman kapag nilikha mo ang iyong bono, isinusuko mo ang iyong bahagi sa LP. Binabayaran ka ng protocol ng mas maraming GYRO kaysa sa makukuha mo sa market, ngunit ang iyong exposure ay nagiging ganap sa GYRO at hindi na sa GYRO-USDT LP.&#x20;

Tandaan na ang sGYRO ay ang kita ng protocol na naipon na token at dahil ang mga bonder ay kumikita ng GYRO (hindi sGYRO), ang mga staker ay nakakakuha ng 100% ng mga protocol na kita (binawasan ang cut ng DAO).&#x20;

**Bakit Gusto Kong Mag-Bond?**&#x20;

Dahil ito ay nagpapahintulot sa iyo na bumili ng GYRO sa isang mas mababang halaga na batayan. Bilang kapalit sa pagbebenta ng iyong LP, ibebenta ka ng protocol ng GYRO nang may diskwento.&#x20;

**Dynamics ng Bond**&#x20;

Sinipi ng protocol ang mga presyo ng bono batay sa risk-free value (RFV) ng protocol. Ang Bond Premium ay isang tool sa patakarang pinamamahalaan ng protocol na kumokontrol sa premium na sinisingil para sa mga bono. Ang mas mababang premium ay nangangahulugan ng mas mataas na diskwento at mas mataas na insentibo sa bond.&#x20;

Executing Price = RFV / Premium {Premium ≥ 1}&#x20;

Ang premium ay tinutukoy ng kabuuang utang ng system at isang scaling variable. Itinatali nito ang presyo ng mga bono sa bilang ng mga natitirang bono; ang mas kaunting mga natitirang bond, mas mababa ang premium at mas mataas ang diskwento.&#x20;

Premium = 1 + (Debt Ratio \* BCV)&#x20;

Debt Ratio = Bonds Outstanding / GYRO Supply&#x20;

Ang risk free na halaga ng bahagi ng LP para sa protocol ay ang punto kung saan balanse ang pool (1 GYRO = 1 USDT). Dahil dapat protektahan ng protocol ang pag-back up ng GYRO, ito ang pinakamababang presyo na maaari nitong tanggapin; pinakamasama kaso, maaari itong bumalik sa bawat 2 GYRO bonded ng 1 USDT at 1 GYRO. Sa itaas ng equilibrium na ito, mayroong labis na USDT. Sa ibaba ng ekwilibriyong ito, mayroong labis na GYRO. Maaaring gamitin ang alinman, at palaging magiging sapat ang pareho.&#x20;

Risk-Free Value = (LP / Total LP) \* 2sqrt(Constant Product)&#x20;

Nangangahulugan ito na ang isang bonder ay (pangkalahatan) nagbebenta ng kanilang LP para sa mas mababang halaga sa merkado. Gayunpaman, kinansela ito ng protocol bonding na GYRO sa mas mababa sa market value.&#x20;

**Linear Scale**&#x20;

Ang exponential na pagtaas sa halaga ng bonded GYRO na may kaugnayan sa halaga ng LP ay inaasahang lilikha ng pagtaas ng demand para sa mga bono sa mas mataas na presyo. Ito ay isang lubhang kanais-nais na dynamic; mas mataas ang presyo (at mas maraming ibinebenta ang protocol bilang tugon), mas maraming pagkatubig ang dapat.&#x20;

Maaaring gawin ng mga Bonders ang kalakalan na ito, sa kabila ng panganib sa oras, dahil ang kanilang breakeven point ay nabawasan. Kung mas mataas ang presyo, mas malaki ang nagiging padding.

**Konklusyon**&#x20;

Ang layunin ng Gyro ay mag-alok ng bagong asset class token na maaaring maging bahagi ng anumang portfolio. Maaari itong gamitin para i-hedge ang mga mapanganib na asset habang nag-aalok ng mas ligtas at mas magandang insentibo kaysa sa mga stablecoin.

