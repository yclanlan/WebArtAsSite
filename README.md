## How to host github page in cargo subdomain!

<hr>


<!-- ### Github Documentation of how to host -->


<!-- <a href="https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#dns-records-for-your-custom-domain">
<img width="796" alt="截圖 2024-02-19 下午1 12 52" src="https://github.com/yclanlan/WebArtAsSite/assets/97862198/ec17cce0-3c98-4e27-8028-afcbe96d0077">
Click to check the document by github</a> -->


## Let's start from setting subdomain in CARGO

### 1. GO this link to find your DNS first!

https://u.cargo.site/account/domains/

(on the top left corner, click into your account!)


### 2. Go the "Edit DNS" 

<img width="785" alt="截圖 2024-02-19 下午1 17 45" src="https://github.com/yclanlan/WebArtAsSite/assets/97862198/906927f4-2aee-4db3-b1b4-f43ef4c6688c">

### 3. click 'Add record' 
### 4. change type to 'CNAME'

![螢幕錄影 2024-02-19 下午1 28 59](https://github.com/yclanlan/WebArtAsSite/assets/97862198/2aa35be5-a561-41da-abe4-8441f42e7eef)


### 5. First Column: type 'the SubDomain Name You Want.your DomainName.com.' 

#### For example: <br>
bread.yichunlan.com<br>
something.yichunlan.com<br>
mygithubbutwanttohoseon.yichunlan.com<br>
<br>
...remember change the domain name to yours!<br>

<!-- (remember the last '.', cargo will change the link directly to "github" when you chick "save") -->

<hr/>

### 6. Second Column: 'your Github UserName .github.io'
#####For example: <br>
yclanlan.github.io<br>
userlanlan.github.io<br>
justtypeyourusername.github.io<br>

<!-- (remember the last '.' again") -->

<hr/>

#### 7. put the subDomain to your github page setting
Go to your repository, click 'setting' then go to the 'pages' tab on the left side, find the custom domain, put the subdomain in! ( The thing you put in at the step5. the first Column)

![螢幕錄影 2024-02-19 下午1 43 12](https://github.com/yclanlan/WebArtAsSite/assets/97862198/6e07dc05-9e87-4885-bd40-2d6f33a2f1a2)

#### 7-1. If you have't publisded your website as a github page.
-> remember to turn the repository to public firts.

when you click into the 'setting', scroll down to see the danger zone, which have the private and public setting!

then go to the 'pages' tab to select the root you want to publish! After these two steps you should can put the subdomain to your page!

![螢幕錄影 2024-02-19 下午2 10 09](https://github.com/yclanlan/WebArtAsSite/assets/97862198/a57035e9-aeeb-47e2-b5e2-18fccdd182d9)





### 8.Wait!! It will take a while, so be patient!!

I waited about half hour to make it happen!




