# ClearURLs-custom-rule
ClearURLs-custom-rule bases on the official ClearURLs's rule and add some additional rules for MYSELF. There might be some mistakes or rules that break functionalities of the website. So that why I didn't not pull request to the official.

## ClearURLs-custom-rule url
- data.json: https://raw.githubusercontent.com/Kristol-Ice/ClearURLs-custom-rule/main/data.json
- rules.hash: https://raw.githubusercontent.com/Kristol-Ice/ClearURLs-custom-rule/main/rules.hash

### Additional rules
"pp" , //added
"eav", //added
"sfnsn", //added
"idorvanity", //added
"wtsid", //added
"rdc", //added
"rdr", //added
"paipv", //added
"_nc_x", //added
"_rdr", //added
"mibextid" //added
"urlPattern": "^https?://(?:[a-z0-9-]+\\.)*?nikkei\\.co(?:m|\\.jp)",
"urlPattern": "^https?://(?:[a-z0-9-]+\\.)*?kahoot\\.it",
"shopee" site //added
"publish_id", // doesn't need
"sp_atk", // doesn't need
"xptdk" // doesn't need
"lazada" site //added
"clickTrackInfo", //as the name says use for tracking 100%
"up_id", // doesn't need (link of seller from home page)
"abid", // doesn't need (link of seller from home page)
"pvid", // doesn't need (link of another item from item info page/link item from home page)
"ad_src", // as the name says use for tracking 100% (link of another item from item info page) and doesn't need
"spm", //maybe use for tracking (link from home,seach, item info page to some campaign / search url) and doesn't need
"src", //use for tracking (link item from home page only) and doesn't need | Example: src=hp_categories
"from", //use for tracking (link item from search result page / home page) and doesn't need | Example: from=hp_officialstore
"scm", //doesn't need (link item from home page/some in search result page)
"pa", //use for tracking (link of another item from item info page) and doesn't need | Example: pa=sponsored_bottom
"pid_pvid", // (link of another item from item info page/link item from home page) and doesn't need
"cid", // doesn't need (link of another item from item info page)
"member_id", // doesn't need (link of another item from item info page)
"pdp_item", // doesn't need (link of another item from item info page)
"did", // doesn't need (link of another item from item info page)
"ncid", // doesn't need (link of another item from item info page)
"adgroup_id", // doesn't need (link of another item from item info page)
"item_id", // doesn't need (link of seller from home page)
"up_id", // doesn't need (link of seller from home page)
"search", // use for tracking, doesn't need (link of seller from cart page/home page/popup when add item to cart) Example: search=addtocart, search=0
"pvtime" // may be time that generate tracking link? (link of another item from item info page) and doesn't need
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