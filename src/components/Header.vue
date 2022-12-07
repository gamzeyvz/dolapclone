<template>
 <header id="header" class="home-page">
    <div class="container">
        <div class="logo">
            <a href="/">
                <img class="logo-title visible-xs" src="/images/logo-5.svg" alt="Dolap" />
                <div class="text-img">
                    <img class="hidden-xs" src="/images/logo-5.svg" alt="elden ele moda" />
                </div>
            </a>
        </div>
        <div class="nav-area">
            <a href="#" class="nav-opener"><span></span></a>
            <div class="list-holder">
                <ul id="nav">
                    <li class="navigationItem hidden-xs"><a href="/markalar">Markalar</a></li>
                    <li class="navigationItem visible-xs"><a rel="nofollow" href="/">Ana Sayfa</a></li>
                    <li class="navigationItem visible-xs"><a rel="nofollow" href="/nasil-calisir">Nasıl
                            Çalışır?</a></li>
                    <li class="navigationItem visible-xs"><a rel="nofollow" href="http://destek.dolap.com"
                            target="_blank">Dolap Destek</a></li>
                    <li class="navigationItem visible-xs"><a rel="nofollow" href="/hakkimizda">İletişim</a></li>
                    <li class="navigationItem visible-xs"><a href="/markalar">Markalar</a></li>
                    <li class="navigationItem hidden-xs">
                        <a rel="nofollow" href="/giris">GİRİŞ YAP</a>
                    </li>
                    <li class="navigationItem visible-xs">
                        <a rel="nofollow" href="/giris">Giriş Yap</a>
                    </li>
                </ul>
                <div class="logo-holder visible-xs">
                    <a href="/"><img alt="Dolap elden ele moda" src="/images/logo-2.svg" /></a>
                </div>
            </div>
        </div>
        <form class="search-form" onSubmit="if (this.q.value.trim() == '') {return false;}" action="/ara">
            <input id="search" type="search" name="q" placeholder="Ürün, @üye, #etiket ara" value="" />
            <a href="#" class="form-opener"><i class="icon-search"></i></a>
        </form>
    </div>
    <div class="links-list">
        <button data-toggle="collapse" data-target="#demo" class="links-opener">
            Kategoriler <i class="icon-down-open"></i>
        </button>
        <ul class="links-ul accordion collapse" id="demo">
            <li class="category-header-93">
                <a href="#" class="opener visible-xs visible-sm">Giyim</a>
                <a class="hidden-xs hidden-sm" href="/giyim">Giyim</a>
                <div class="slide">
                    <ul class="inner-links">
                        <li>
                            <a href="/ust-giyim" title="Üst Giyim">
                                <div class="icon-holder">
                                    <img src="/images/94.png" alt="Üst Giyim" width="40" height="40" />
                                </div>
                                <span>Üst Giyim</span>
                            </a>
                        </li>
                        <li>
                            <a href="/alt-giyim" title="Alt Giyim">
                                <div class="icon-holder">
                                    <img src="/images/105.png" alt="Alt Giyim" width="40" height="40" />
                                </div>
                                <span>Alt Giyim</span>
                            </a>
                        </li>
                        <li>
                            <a href="/elbise" title="Elbise">
                                <div class="icon-holder">
                                    <img src="/images/126.png" alt="Elbise" width="40" height="40" />
                                </div>
                                <span>Elbise</span>
                            </a>
                        </li>
                        <li>
                            <a href="/dis-giyim" title="Dış Giyim">
                                <div class="icon-holder">
                                    <img src="/images/115.png" alt="Dış Giyim" width="40" height="40" />
                                </div>
                                <span>Dış Giyim</span>
                            </a>
                        </li>
                        <li>
                            <a href="/plaj-giyim" title="Plaj Giyim">
                                <div class="icon-holder">
                                    <img src="/images/370.png" alt="Plaj Giyim" width="40" height="40" />
                                </div>
                                <span>Plaj Giyim</span>
                            </a>
                        </li>
                        <li>
                            <a href="/ev-giyim" title="Ev Giyim">
                                <div class="icon-holder">
                                    <img src="/images/374.png" alt="Ev Giyim" width="40" height="40" />
                                </div>
                                <span>Ev Giyim</span>
                            </a>
                        </li>
                        <li>
                            <a href="/" title="İkili Takım">
                                <div class="icon-holder">
                                    <img src="/images/34000.png" alt="İkili Takım" width="40" height="40" />
                                </div>
                                <span>İkili Takım</span>
                            </a>
                        </li>
                    </ul>
                </div>
            </li>
            <li class="category-header-73">
                <a href="#" class="opener visible-xs visible-sm">Çanta</a>
                <a class="hidden-xs hidden-sm" href="/canta">Çanta</a>
                <div class="slide">
                    <ul class="inner-links">
                        <li>
                            <a href="/kol-cantasi" title="Kol Çantası">
                                <div class="icon-holder">
                                    <img src="/images/78.png" alt="Kol Çantası" width="40" height="40" />
                                </div>
                                <span>Kol Çantası</span>
                            </a>
                        </li>
                        <li>
                            <a href="/askili-canta" title="Askılı Çanta">
                                <div class="icon-holder">
                                    <img src="/images/82.png" alt="Askılı Çanta" width="40" height="40" />
                                </div>
                                <span>Askılı Çanta</span>
                            </a>
                        </li>
                        <li>
                            <a href="/sirt-cantasi" title="Sırt Çantası">
                                <div class="icon-holder">
                                    <img src="/images/74.png" alt="Sırt Çantası" width="40" height="40" />
                                </div>
                                <span>Sırt Çantası</span>
                            </a>
                        </li>
                        <li>
                            <a href="/cuzdan" title="Cüzdan">
                                <div class="icon-holder">
                                    <img src="/images/76.png" alt="Cüzdan" width="40" height="40" />
                                </div>
                                <span>Cüzdan</span>
                            </a>
                        </li>
                        <li>
                            <a href="/portfoy-el-cantasi" title="Portföy/El Çantası">
                                <div class="icon-holder">
                                    <img src="/images/77.png" alt="Portföy/El Çantası" width="40" height="40" />
                                </div>
                                <span>Portföy/El Çantası</span>
                            </a>
                        </li>
                        <li>
                            <a href="/plaj-cantasi" title="Plaj Çantası">
                                <div class="icon-holder">
                                    <img src="/images/81.png" alt="Plaj Çantası" width="40" height="40" />
                                </div>
                                <span>Plaj Çantası</span>
                            </a>
                        </li>
                        <li>
                            <a href="/makyaj-cantasi" title="Makyaj Çantası">
                                <div class="icon-holder">
                                    <img src="/images/80.png" alt="Makyaj Çantası" width="40" height="40" />
                                </div>
                                <span>Makyaj Çantası</span>
                            </a>
                        </li>
                        <li>
                            <a href="/seyahat-cantasi" title="Valiz / Bavul">
                                <div class="icon-holder">
                                    <img src="/images/75.png" alt="Valiz / Bavul" width="40" height="40" />
                                </div>
                                <span>Valiz / Bavul</span>
                            </a>
                        </li>
                        <li>
                            <a href="/" title="Bel Çantası">
                                <div class="icon-holder">
                                    <img src="/images/513.png" alt="Bel Çantası" width="40" height="40" />
                                </div>
                                <span>Bel Çantası</span>
                            </a>
                        </li>
                        <li>
                            <a href="/canta-diger" title="Diğer">
                                <div class="icon-holder">
                                    <img src="/images/83.png" alt="Diğer" width="40" height="40" />
                                </div>
                                <span>Diğer</span>
                            </a>
                        </li>
                    </ul>
                </div>
            </li>
            <li class="category-header-63">
                <a href="#" class="opener visible-xs visible-sm">Ayakkabı</a>
                <a class="hidden-xs hidden-sm" href="/ayakkabi">Ayakkabı</a>
                <div class="slide">
                    <ul class="inner-links">
                        <li>
                            <a href="/spor-ayakkabi" title="Spor Ayakkabı">
                                <div class="icon-holder">
                                    <img src="/images/67.png" alt="Spor Ayakkabı" width="40" height="40" />
                                </div>
                                <span>Spor Ayakkabı</span>
                            </a>
                        </li>
                        <li>
                            <a href="/babet" title="Babet">
                                <div class="icon-holder">
                                    <img src="/images/64.png" alt="Babet" width="40" height="40" />
                                </div>
                                <span>Babet</span>
                            </a>
                        </li>
                        <li>
                            <a href="/ince-topuklu" title="İnce Topuklu">
                                <div class="icon-holder">
                                    <img src="/images/70.png" alt="İnce Topuklu" width="40" height="40" />
                                </div>
                                <span>İnce Topuklu</span>
                            </a>
                        </li>
                        <li>
                            <a href="/kalin-topuklu" title="Kalın Topuklu">
                                <div class="icon-holder">
                                    <img src="/images/69.png" alt="Kalın Topuklu" width="40" height="40" />
                                </div>
                                <span>Kalın Topuklu</span>
                            </a>
                        </li>
                        <li>
                            <a href="/dolgu-topuklu" title="Dolgu Topuklu">
                                <div class="icon-holder">
                                    <img src="/images/71.png" alt="Dolgu Topuklu" width="40" height="40" />
                                </div>
                                <span>Dolgu Topuklu</span>
                            </a>
                        </li>
                        <li>
                            <a href="/oxford-loafer" title="Oxford/Loafer">
                                <div class="icon-holder">
                                    <img src="/images/72.png" alt="Oxford/Loafer" width="40" height="40" />
                                </div>
                                <span>Oxford/Loafer</span>
                            </a>
                        </li>
                        <li>
                            <a href="/sandalet" title="Sandalet">
                                <div class="icon-holder">
                                    <img src="/images/68.png" alt="Sandalet" width="40" height="40" />
                                </div>
                                <span>Sandalet</span>
                            </a>
                        </li>
                        <li>
                            <a href="/terlik" title="Terlik">
                                <div class="icon-holder">
                                    <img src="/images/132.png" alt="Terlik" width="40" height="40" />
                                </div>
                                <span>Terlik</span>
                            </a>
                        </li>
                        <li>
                            <a href="/bot" title="Bot">
                                <div class="icon-holder">
                                    <img src="/images/65.png" alt="Bot" width="40" height="40" />
                                </div>
                                <span>Bot</span>
                            </a>
                        </li>
                        <li>
                            <a href="/cizme" title="Çizme">
                                <div class="icon-holder">
                                    <img src="/images/66.png" alt="Çizme" width="40" height="40" />
                                </div>
                                <span>Çizme</span>
                            </a>
                        </li>
                        <li>
                            <a href="/" title="Topuklu Sandalet">
                                <div class="icon-holder">
                                    <img src="/images/34250.png" alt="Topuklu Sandalet" width="40" height="40" />
                                </div>
                                <span>Topuklu Sandalet</span>
                            </a>
                        </li>
                    </ul>
                </div>
            </li>
            <li class="category-header-84">
                <a href="#" class="opener visible-xs visible-sm">Aksesuar</a>
                <a class="hidden-xs hidden-sm" href="/aksesuar">Aksesuar</a>
                <div class="slide">
                    <ul class="inner-links">
                        <li>
                            <a href="/gozluk" title="Gözlük">
                                <div class="icon-holder">
                                    <img src="/images/86.png" alt="Gözlük" width="40" height="40" />
                                </div>
                                <span>Gözlük</span>
                            </a>
                        </li>
                        <li>
                            <a href="/saat" title="Saat">
                                <div class="icon-holder">
                                    <img src="/images/85.png" alt="Saat" width="40" height="40" />
                                </div>
                                <span>Saat</span>
                            </a>
                        </li>
                        <li>
                            <a href="/taki" title="Takı">
                                <div class="icon-holder">
                                    <img src="/images/91.png" alt="Takı" width="40" height="40" />
                                </div>
                                <span>Takı</span>
                            </a>
                        </li>
                        <li>
                            <a href="/kemer" title="Kemer">
                                <div class="icon-holder">
                                    <img src="/images/87.png" alt="Kemer" width="40" height="40" />
                                </div>
                                <span>Kemer</span>
                            </a>
                        </li>
                        <li>
                            <a href="/sal" title="Şal/Eşarp">
                                <div class="icon-holder">
                                    <img src="/images/88.png" alt="Şal/Eşarp" width="40" height="40" />
                                </div>
                                <span>Şal/Eşarp</span>
                            </a>
                        </li>
                        <li>
                            <a href="/eldiven" title="Eldiven">
                                <div class="icon-holder">
                                    <img src="/images/135.png" alt="Eldiven" width="40" height="40" />
                                </div>
                                <span>Eldiven</span>
                            </a>
                        </li>
                        <li>
                            <a href="/atki" title="Atkı">
                                <div class="icon-holder">
                                    <img src="/images/133.png" alt="Atkı" width="40" height="40" />
                                </div>
                                <span>Atkı</span>
                            </a>
                        </li>
                        <li>
                            <a href="/bere" title="Bere">
                                <div class="icon-holder">
                                    <img src="/images/134.png" alt="Bere" width="40" height="40" />
                                </div>
                                <span>Bere</span>
                            </a>
                        </li>
                        <li>
                            <a href="/sapka" title="Şapka">
                                <div class="icon-holder">
                                    <img src="/images/89.png" alt="Şapka" width="40" height="40" />
                                </div>
                                <span>Şapka</span>
                            </a>
                        </li>
                        <li>
                            <a href="/sac-aksesuarlari" title="Saç Aksesuarları">
                                <div class="icon-holder">
                                    <img src="/images/90.png" alt="Saç Aksesuarları" width="40" height="40" />
                                </div>
                                <span>Saç Aksesuarları</span>
                            </a>
                        </li>
                        <li>
                            <a href="/corap" title="Çorap">
                                <div class="icon-holder">
                                    <img src="/images/362.png" alt="Çorap" width="40" height="40" />
                                </div>
                                <span>Çorap</span>
                            </a>
                        </li>
                        <li>
                            <a href="/aksesuar-diger" title="Diğer">
                                <div class="icon-holder">
                                    <img src="/images/92.png" alt="Diğer" width="40" height="40" />
                                </div>
                                <span>Diğer</span>
                            </a>
                        </li>
                        <li>
                            <a href="/" title="Gelin Buketi">
                                <div class="icon-holder">
                                    <img src="/images/629.png" alt="Gelin Buketi" width="40" height="40" />
                                </div>
                                <span>Gelin Buketi</span>
                            </a>
                        </li>
                        <li>
                            <a href="/" title="Şemsiye">
                                <div class="icon-holder">
                                    <img src="/images/34950.png" alt="Şemsiye" width="40" height="40" />
                                </div>
                                <span>Şemsiye</span>
                            </a>
                        </li>
                    </ul>
                </div>
            </li>
        </ul>
    </div>
</header>
  </template>
  
  

 
