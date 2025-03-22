And I revamped it yet again. I realized it makes no sense to have UI and Ads split into two lists. The idea made sense at first, but after some thoughts, it doesn't. Some sites don't have any ads, so I would just update one. And with some things it's difficult to decide if it's an ad or UI. The names got shorter (removing the weird `%20` from `1.2%20-%20Desktop%20UI`), so now it's just `Desktop.txt` and `Mobile.txt` (yes, I also forgot to add the `.txt`).
Meaning it's only a list for Desktop and one for Mobile, instead of four. Some things only appear when you are on mobile (mobile-sized ad-fields) and some only appear on Desktop. So I will not mix them. The new `Ads.txt` will be for things like `ads.js`, image-based ads a DNS blocker cannot get rid of (because they come from the same URL as the main page) or things I blocked in my DNS. The Desktop/Mobile lists are only UI elements. And this time, I will make a proper dokumentation (comments), as I already planned before.

Yes, you might ask, why don't split `Ads.txt` as well. But I don't want to. In fact, I can't, since there is no console on mobile and I can't check if some .js things get loaded there or not. And when I blocked it in my DNS, it will get blocked on all devices anyways.


As before, there will be three labels for Commits:
`Added`: A site has been added the first time
`Improved`: More rules for an existing site
`Fixed`: Something didn't work


But why am I even doing this in the first place, when there are plenty of lists out there? Well, they are mostly for ads. I use a DNS for blocking these and even without I already had a ton of rules for removing clutter. But it proved to be difficult to sync it to mobile Firefox, so I decided to put it here and just add the links. Then I only need to refresh them using the little clock button.
`https://raw.githubusercontent.com/DeepSpace1701/Operation-Clean-Web/main/Ads.txt`
`https://raw.githubusercontent.com/DeepSpace1701/Operation-Clean-Web/main/Desktop.txt`
`https://raw.githubusercontent.com/DeepSpace1701/Operation-Clean-Web/main/Mobile.txt`

That aside, I only use two lists for Cookies: `AdGuard – Cookie Notices` and `uBlock filters – Cookie Notices`.