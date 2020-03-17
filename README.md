# Seattle Cast

## Problem Statement
Our mission is to design a database system for Seattle Cast, a podcast network in the Seattle area, so they can efficiently aggregate download data and calculate key metrics for measuring podcasts’ success. Building an efficient database system will improve existing listener analytic strategies, equipping them to make better business decisions for their audience and attract more lucrative advertising campaigns. 

## Description
Seattle Cast is a new podcast network with ten Seattle-based podcasts: sports, tech, food, music, comedy, news and outdoor activities. Each of these podcasts already has multiple episodes available for download via Apple’s podcast application. People can subscribe to a podcast, ensuring that each new episode will be automatically downloaded to their listening device. Or, without subscribing, people can manually download individual episodes of the podcast. For Seattle Cast, podcast episodes have three advertisement slots: pre-roll (before episode content), mid-roll (in the middle of episode content), and post-roll (after episode content).   
Seattle Cast’s goal is to attract more sponsors so they can fill all open advertisement slots on upcoming episodes and establish a more consistent revenue stream from their podcasts. To attract and retain the right sponsors, they need robust analytics about the people who download and subscribe to their podcasts. Our custom database system will equip Seattle Cast to make sure all advertising slots are filled, track the success of advertising campaigns, and easily extract the metrics and insights needed to attract future sponsors as well as choose the right campaigns to match their audience. 

### Tableau Public site
https://public.tableau.com/views/PodcastVisualizations/PocastMetrics?:display_count=y&publish=yes&:origin=viz_share_link

### ER Diagram
[Seattle Cast](https://app.diagrams.net?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1#R7V1rc5u6Fv01mTn3QzKIhzEfnUfTniZtmrSnp%2FdLRzaKTYuRL%2BAm7q%2B%2FkpEwINk8bMAuZDJtkAHbWmtvbS32ls60q%2FnrrQ8Xs3tsI%2FdMVezXM%2B36TFVVzVTJf7RlxVp0YEQtU9%2BxozawaXhyfiPWqLDWpWOjIHViiLEbOot04wR7HpqEqTbo%2B%2FglfdozdtPvuoBTJDQ8TaArtn517HAWtQ5Vc9P%2BFjnTGX9nMLCiV%2BaQn8y%2BSTCDNn5JNGk3Z9qVj3EY%2FTV%2FvUIu7T3eL1%2Ffrb66dz8Ht39%2FCv4Hv1y%2B%2F%2Fzhn%2FPoZm%2FKXBJ%2FBR95YeVbmx9fv8zwYjRx%2Fqt9%2BDS7eo%2F%2Btc%2BBobEvF654jyGbdCA7xH44w1PsQfdm03rp46VnI3pfhRxtzrnDeEEaAWn8gcJwxdgAlyEmTbNw7rJXyffwV%2F%2By69cH3%2BjBhcEPr1%2BTL16v2FEQ%2BvhnjKNGWgp2DevCAC%2F9CdrVHzrjewj9KQp3nGkMoxNpbyWYxvr%2BFuE5Ip%2BcnOAjF4bOrzQdIWP1ND6PXTryfbhKnLDAjhcGiTs%2F0AZyArNQoA4YPZmBapqZpkHeBUPFSl5A%2Fog%2BAz9KfJlN05pbpXg2iN70F3SXrCsE4tkwmMWsgsEicgfPzittvPyF%2FNAhdn0Hx8h9wIETOtgjr49xGOJ54oSR60zpCyEl4yVkRxNCEORTDs3ggr7h%2FHVKXd7FdG67FwHBO%2BbXFXaxv%2F5ImqrpukHf%2Fdlx3UT7GE6GthbdLXIKSmky0s%2BLXndyh71qqkYKMu6RXjYOzeBts4QzixtldEsAXgFPRcnHM9%2BRPGMvZE4CqFkXYY%2Bo%2ByeHN4%2FYQ5%2FxPfRWa4ygH25emkPP%2FuihPZwKenXC9WUXujpkx9GV1tBkx5tL6UHyygfkO6RPKbUqcCDXIVlWQX%2FErTrXHyVIE6OYJE3cWM5xCY4mHmIZaQ0zQ8bou7Ordnis7I1MK3OjqG%2BEGx3Kdw2HR0z1Dbu%2FpcidR3UjQXRwoWjDtomuaQWJbppHRnQQM5u7Z60i00F8Jb9T1oFvofr2qOHgxmA1aQy%2FkY8LWIOU1cpuRm8sSDeHSRsCFwDkDhn0qGaD4BFTrkEMtWMzCC1DY31Q1SAMJX2nQda0ShvEljfSrUF6kDFTs6maomJuPLus6cC2UnXkyLVpboUgFUIZO62wrWAJAHBkNqMP0kGOVt1kQMZk9HpMRjfTkxJt2MQ8UtWOLxirQPyqc5UDGwwAelGLUYwjsxiB6GpVkxka6RsZA62QxRyO1MbxkZoTFJQjaJVY7NCBU0FKc6H3eBitqWkigsqDgJK1DdDsnHkgyn0P2J7AIPx%2BtQxCcn9fYHjw4sxd6MVUZq9QhkxmjmvfwRVe0i4npJ385EeXM%2Bw7v8n5kJN9zWlmCOogdcYTvZLd00cBOeeBsw5kmu7ha%2BrEO%2FLZ%2BafBrgsXgTNefz564Zz0puNdMiUykqrZt3mTFg6f1z8yXTJpvnqNYqJmpalxrnH6Jnk%2BkPF8qG6n9F5yIg9%2BdjrAjQ%2Fz8JolSQcXux1FSWp456TBADu9TzFtYyfLc11SFVdjSBAwDuNozvX0eJe5QWEvk3mSkL1P7cOmvs3JvCN%2FK%2B8%2BfCb%2F%2FvXm%2FX8ELhFTCQW5n7Eqq%2FQD235eG%2FQCThxveoeeKRj6puWR4UObMLHDZ3dN0plj28hbPy0LYQjHsTNjgTW5u3FJfkkfXtHR0iDvdkWOweaY%2FNLT%2FfAKe%2BSzQmfNRkS%2B4Aui3kgY8kvytoDTiGOrYi6Cn3d4DyGKsHwg6cE%2BMNiG2jbYosj4tBwHE98Z07hBuXo7evwL9EjvjbQ5bBlprpyLSC%2Fo491rGCLy6vXo883nd%2Fc3PeD7Ag4UvW3EgYD4I%2FrloBfS9s%2FoMTJtRemOcfOJgLv%2BkDVCrxUM8%2BuDXlS7H0kY602piX%2F8cnnXHQNvDHSj7cDNLKJt7ZraleybI5lisS8Zpyykry8u5g933qfuGZZWIGvr1FIfSqj0cUKanIf7Se%2FcHefqlNaxPasyMzKlmk3IKSy8Z6Sogd6wgqCJutMznITfr%2FGL52JoBwLbe5GyEZFymE2p0cVxLE6WSXHcqGsgA1qRPLDjEyljkhdIfq7gaXqZMo83ujjj6WXKUszdS6eUuonawl2giwkKXRcqq012KqAvES6bRl%2Bc4t4snADb6D1adRP9%2BuCWqJdNwy0%2BgeoVjZqNXCZhNg37vprGJrvmQgGZDBtLV%2FOmssWyj3d3eNsxXhbNslEdmSNcGKoV%2F2SyEcl9L3RLVfgPaFg50SXPK11n8jP46I3otDIaCXrfcGDfING4G%2FYNhsQVNFhQWzJdr4GCWl70nStz6QUdU2GPsxeQoovvE9fa1YRIcJ3JXLOKPtxQhjWxRBXn9iUjgVY0IaOg9R5JrPBH6UHiIxVRH%2BhIXFCOrSeUrSY%2BVnjzAc5pKgtPcdCNXgHYF%2BbW89TEGP%2Buh%2FngMLeepMbH9ATO13h81sG8tGoTudKIt5%2Blpolx3S2J4zqZfdoU6K3np2mimnszh47bUX%2FeFO6tp6hpkkd2eOlFn5Ijr%2FYpqQdHnteTtYa8cTAhX7mwrKT0Bi6UtYRTl45fuMj17Khm8OwKHsBn6qyLzuDPtUx6UFzC2NAc3hQneOwxb1%2Fe2rpKmCl91nRJXDFsNHXMPM3MMbNo4hjvzWPxMn%2BETshzvUUf09U8opK03U8vlHmI%2BoQksQyuTxGsB2uZaNgs1qK00PUEwdrAlkmHzYItkQ5hiD4%2B8wqDXkWsD32pjNgs%2FBJloc8Cqht2mZDYLOyikFgt3qfxPUivK1dlqd6USqEnZYrcqrk9JIri0wfWO%2FkrnapHNc9Iixkgq0EUnmcMc25Ud66iIkYkTwti1LgXMdoqfxMKIyUuzZK5tNoynYAihjLVnFrD5W%2Bc3fmpikrRDMRexijDGzEGYt6lz3fKc8h7KRhS%2F1Bb3rMixjwM5j4lpgbAZTJGw4CLz87eefYySD827dE%2BBNoyHaNhtCVpqzRcm4RdzmysWNhSngBSKaNhBojPPEk3EQJ0OeexOQLIRI2GCSA%2BxezTo5qAXpYg1TD04rNI5v0%2F4B7%2BmuGXZUk1Cz%2FPqDi9NKm4vwtscFFhG6U%2BVaoAebYuf%2FO9Vxnb3QlgWFFlrG8jAABOVGXkLC%2B%2B5c6x%2BJk%2FQ2WUFOL2GTSlmHtKYiMooCn3aB8G7faVRiBKyyM7WODwrJvlGfVh3b7OCERV%2BYlGcf1OAIfG%2BggkRSCKyjee3VWoKyoKFZBvX0sEEjH5YeR4X57o%2BN0vnVcT8O0rierBpCRh2bxYWKpDRwKFdSRwJCV3MeZG%2BpKTUY4MyegQFcAIjOkFo6Zq67QUJfgu6flbR9ZWW2ec5taRvD%2Fyd7Ptt46swbVIHmVma%2Bs6EnyU5OsJLcJliA8te0mwHqxbX4lrIIaVd8ibhrN33r3jBd2bU9QGdeurcQ1Epf8axTtGnvXZCHWi3%2F7KXANVhH9dUXkHl95k1gtHNYLf%2Bgpdg4Ou1xMnnjAFIT6hjvV6WJfk6gfHFu%2Bn01DMDLInIyaAIks9Fd2o8DfycZmdCtM8y1uTPX%2B5%2BM2UVeUbGMbFnFsnqyJR91rY3SoqiA0qELrW7QuFBYKsirtz6sP0nhMDoxinCVngKnEaGxq2fmBNSe8Ceq6yfMyNjUS3PKjFWGKcxaZPgt308lsj8puaEU1kmyLK87VqU98sMRorOSC3or5Zhb1cn6x1%2BLHYEvM5BGGmI6F7Sb6eUI6WJcZbDOQOlwvVBnfrSVqW%2BLDuLe6u0lptSl4e99YTtixJIgcM0RSnqoBBh2y8Kejbz9%2By9l7WtC01pvDk9djiv0xRUMUVh1pXY%2FiMO5nliScOdO%2BR7cAHH5G5VUCDhH6vhZqcR%2FspgKo8YhCg7sWFVorBztWCYn%2BNxWDqaeb2xNTOLwZTj0zt%2FyP0BaCKgUl6MtKR0aQsX08ouSe2nH6PvZqhbj23J45V%2Bn32aoa69dweINl3rd9qr8RMoALo7af0AE0VUO9326sd99azeYBk47V%2BRakmoG99yz2gnezOa3F%2F55eC8XnIsczuTm9JoavR9Fb9%2B9tA%2FXJrToMfn6bK5eRcDAeDaPGH4EwduNR0xmTkGEw3RiQ6jwSTcv0IaxKkGWpwzgS6I%2FbCnPiMdX7Wy8wJ0RPxL%2FQ9X3y4WPuRJRnR7BTXBIstKuxsVXHMgZmCxlREJy8zdD4C72PoUqxED%2B%2FQbPwZmY6TzlCV8apjCGlGWmMBQzHolgmxtSEkyrATKoquqya6hYyedmtDSXFjo7Yjqp9r27HZ1kGx%2FXTc5wEtu1uCJYlsZRmltSEnalMctK4ZFdB5uLQj9mzUqiQrzAXLMS0gGqOABvEkzoIh%2FVOBnr2Oun456KVzwKmZKO9c1Q3RrMxGodsSTcT42Rv87Ax%2BHY02lAyIQBIQNgyimP0ZgRjF8N3ESc88fdX5bjutDWGStZkm8dbWSmI4UyD9%2BlsqA%2F5s1AYZ65Im5GuNoibGjNtQo6WyiK%2BnouDnk0ByrcbRMt%2BaBz%2BQmQtouuTRiNoosuIz7RgqNtBt0Fw71DFyvKlsvrDGebJtn%2FrjALq%2BsMZIF23FmcspmzXqQXZLaaIugJBfA5jurs05dxgvGG4%2FUBiumMAMlyHeJqCelSpPjNjwlfWWJhVO96osBDoL8%2FJLC6PzcuXVcrpp2fI8kK3L0thiYVvTY7IX8EWMKtbzkUMf4zB5OjGp2T3xBfSM%2FwM%3D)
