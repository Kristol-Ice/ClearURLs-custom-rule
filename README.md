# ClearURLs-custom-rule
ClearURLs-custom-rule bases on the official ClearURLs's rule and add some additional rules for MYSELF. There might be some mistakes or rules that break functionalities of the website. So that why I don't not pull request to the official yet.

## ClearURLs-custom-rule url
- data.json: https://raw.githubusercontent.com/Kristol-Ice/ClearURLs-custom-rule/main/data.json
- rules.hash: https://raw.githubusercontent.com/Kristol-Ice/ClearURLs-custom-rule/main/rules.hash

### Additional rules
"pp" , //added

"eav" //added url

"sfnsn" //added url

"idorvanity" //added url

"wtsid" //added url

"rdc" //added url

"rdr" //added url

"paipv" //added url

"_nc_x" //added url

"_rdr" //added url

"mibextid" //m.facebook.com when share tracking

"shopee" site //added

"publish_id" // not break

"sp_atk" // not break

"xptdk" // not break

"lazada" site //added

"clickTrackInfo" // as the name says use for tracking 100%

//"up_id" not sure, pattern not look like tracking para, not break (link of seller from home page) | Example: up_id=4946721348

"abid" // not break (link of seller from home page) Example: abid=0,132055555,16681078,12914538,12342418,21386346,21345230,13633424,21393424,21486240,362428,20942286,12903428,12574342,21384284,255555432,8460342,213755555,213342842,12559238,12094245,21388408,21381376,21403532,12656138,12449264,21388438,21393042,21390608,21410078,12189920,21386776,12192856,21432454,21424528,10435570,12950434,18243582,240363,12616746,21382700,19944028,12729388,21397544,13215270,213428562,14620714,16872342,1279551563,123,130554248

"pvid" // not break (link of another product from product info page/link product from home page) | Example: pvid=d13sf242-8743-441f-b068-0a5edads1c21

"ad_src" // as the name says use for tracking 100% (link of another product from product info page) and not break | Example: ad_src=5741_3727:10217,1700_930:0.94342136434248

"spm" //maybe use for tracking (link from home,seach, product info page to some campaign / search url) and not break | Example: spm=a3o1k.home.header.1.1534535fgfsFgc

"src" //use for tracking (link product from home page only) and not break | Example: src=hp_categories

"from" //use for tracking (link product from search result page / home page) and not break | Example: from=hp_officialstore

"scm" //use for tracking, not break (link product from home page/some in search result page/link to other sites) | Example: https://bit.ly/lazada-ios-app?scm=1003.4.icms-zebra-1349781-1645724.OTHER_1645723498_274568

"pa" //use for tracking (link of another product from product info page) and not break | Example: pa=sponsored_bottom

"pid_pvid" // (link of another product from product info page/link product from home page) and not break) | Example: pid_pvid=gpoks093oIHJf0984ojF0i4kjpgd1

// "cid" pattern not look like tracking para, not break (link of another product from product info page)

// "member_id" pattern look like acutal member id of seller, not break (link of another product from product info page)

// "pdp_item" pattern not look like tracking para, not break (link of another product from product info page)

"did" // not break (link of another product from product info page) | Example: did=d13sg232-7243-351f-b068-gkfhops94as4

//"ncid" pattern not look like tracking para, not break (link of another product from product info page)

// "adgroup_id" not sure, not break (link of another product from product info page)

// "product_id" 100% break suggest similar product (link of seller from home page)

"up_id" // not break (link of seller from home page)

// "search"  pattern not look like tracking para, not break (link of similar product from cart page/home page/popup when add product to cart) Example: search=addtocart, search=0, search=cart

//"pvtime" not sure, may be time that generate tracking link? (all of them has the same value) (link of another product from product info page) and not break

// "q" use for search, 100% breaks search function

"pantip.com" site //added

"#lead.*" //as the name says use for tracking 100%

"pixiv.net" site //added

"redditmail.com" site //added

"invol.co" site //added

"addons.mozilla.org" site //added


## ClearURLs breaks Google OAuth/3rd party apps login?
1. disable this <img src="https://github.com/Kristol-Ice/ClearURLs-custom-rules/assets/134151822/9f9a822b-ae7d-4702-9f5e-a231caf65ca8" height="50x">
2. NEED to click <img src="https://github.com/Kristol-Ice/ClearURLs-custom-rules/assets/134151822/e08e0f4c-017a-42e5-9abb-8ea2c553466e" height="50px"> too.

*Disable "Prevent tracking injection over history API" may reduce full ability of this extension.

---

## <sub><img src="https://gitlab.com/ClearURLs/ClearUrls/raw/master/img/clearurls.svg" width="64px" height="64px"></sub> ClearURLs
**ClearURLs** is an add-on based on the new WebExtensions technology and is optimized for *Firefox* and *Chrome* based browsers.

[ClearURLs extension's Github link](https://github.com/ClearURLs/Addon)

<details>
    <summary>the official ClearURLs Rules URL</summary>
    https://rules2.clearurls.xyz/data.minify.json or https://gitlab.com/ClearURLs/rules/-/blob/master/data.min.json
</details>
<details>
    <summary>the official ClearURLs Rules Repository</summary>
    https://github.com/ClearURLs/Rules or https://gitlab.com/ClearURLs/rules
</details>