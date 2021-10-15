# ota-api-doc

API List

Banners 
Read banner - http://creatordesk.otamyanmar.com/banner/read.php
Example Respond - {"records":[{"banner_id":"33","url":"https:\/\/creatordesk.otamyanmar.com\/\/static\/banner\/102789674_168140998091749_3163656856045716223_n.jpg","action":"\/manga\/?manga_id=14","bannerText":""},{"banner_id":"35","url":"https:\/\/creatordesk.otamyanmar.com\/\/static\/banner\/Chainsaw-Man-Chapter-87-Release-Date-Spoilers.jpg","action":"\/manga\/?manga_id=17","bannerText":"\u0000\u0000\u0000C"},]}

Manga
Read recent mangas - https://creatordesk.otamyanmar.com/manga/readtip.php
Read all mangas    - https://creatordesk.otamyanmar.com/manga/read.php
Example respond    - {"records":[{"manga_id":"21","chpt_count":"0","manga_title":"The Ranker Who Live Twice","manga_cover":"https:\/\/creatordesk.otamyanmar.com\/\/static\/manga\/103110343_168197688086080_8697050634944896927_n.jpg","manga_disp":"His brother had been the victim of deceit in this universe as he climbed up the wall.\r\n\r\nAfter learning the facts, Yeon-woo and his brother's diary decided to climb up the tower.\r\n\r\nYeon-woo then goes through the same trials and battles that his younger brother did as an anonymous player.","manga_like_count":"0","created":"2021-10-14 11:14:47","category_id":"1","category_name":"Isekai","draft":"0"},{"manga_id":"36","chpt_count":"0","manga_title":"Untouchable Lady","manga_cover":"https:\/\/creatordesk.otamyanmar.com\/\/static\/manga\/untouchable-lady-64053.jpg","manga_disp":"\u201cPlease, Hilise. Please die in place of Gabrielle.\u201d My always dignified brother begged me for the first time. He wants me to die for our stepsister, whom we don\u2019t even share a drop of blood with. \u201cFor the first and last time, I ask you this.\u201d I\u2019ve always been miserable, and there is no exception this time. The seventh time that I was betrayed and killed, I was completely free of lingering feelings. \u201cI\u2019m glad that you\u2019re a scumbag until the end.\u201d I won\u2019t be swayed by love anymore. It\u2019s my turn to abandon them first.","manga_like_count":"0","created":"2021-10-13 09:43:58","category_id":"3","category_name":"Romance","draft":"0"},]}

Read One manga - https://creatordesk.otamyanmar.com/manga/read_one.php?manga_id= 'id' 
Example Respond - {"manga_id":"21","chpt_count":"0","manga_title":"The Ranker Who Live Twice","manga_cover":"https:\/\/creatordesk.otamyanmar.com\/\/static\/manga\/103110343_168197688086080_8697050634944896927_n.jpg","manga_disp":"His brother had been the victim of deceit in this universe as he climbed up the wall.\r\n\r\nAfter learning the facts, Yeon-woo and his brother's diary decided to climb up the tower.\r\n\r\nYeon-woo then goes through the same trials and battles that his younger brother did as an anonymous player.","manga_like_count":"0","created":null,"category_id":"1","category_name":"Isekai"}

Search Manga - https://creatordesk.otamyanmar.com/manga/search.php?s= 'key word'

Read Manga Chapter List - https://creatordesk.otamyanmar.com/manga/read_Chpt.php?manga_id=21
Example Respond - {"chpts":[{"manga_id":"21","chpt_id":"462","chpt_thumb":"https:\/\/cdn.otamyanmar.com\/thumb\/manga2021101482573.jpg","chpt_sum":"Chapter 99","chpt_num":"99"},{"manga_id":"21","chpt_id":"452","chpt_thumb":"https:\/\/cdn.otamyanmar.com\/thumb\/manga2021100658457.jpg","chpt_sum":"Chapter 98","chpt_num":"98"},]}

Read Chpt Contents - https://creatordesk.otamyanmar.com/manga/read_mgcontent.php?chpt_id= 'id'
Example respond  - {"cont":[{"c_id":"17053","chpt_id":"411","url":"https:\/\/cdn.otamyanmar.com\/content\/mgpan2021091222242.jpeg","c_num":"0"},{"c_id":"17054","chpt_id":"411","url":"https:\/\/cdn.otamyanmar.com\/content\/mgpan2021091247605.jpeg","c_num":"1"},]}


Articles

Read recent Articles - https://creatordesk.otamyanmar.com/article/readtip.php
Example Respond - {"articles":[{"art_id":"1","art_title":"MindaRyn : The girl whose dream came true","art_thumb":"https:\/\/creatordesk.otamyanmar.com\/\/static\/lightnovel\/avatars-000309892720-6f2gl0-t500x500.jpg","art_sum":"anime song \u1010\u103d\u1031 cover \u1006\u102d\u102f\u1010\u1032\u1037 \u1011\u102d\u102f\u1004\u103a\u1038 \u1014\u102d\u102f\u1004\u103a\u1004\u1036\u1000 \u1021\u1006\u102d\u102f\u1010\u1031\u102c\u103a\/you tuber \u1000\u1031\u102c\u1004\u103a\u1019\u101c\u1031\u1038 MindaRyn \u1000 \u1014\u102c\u1019\u100a\u103a\u1000\u103c\u102e\u1038 anime \u1016\u103c\u1005\u103a\u1010\u1032\u1037 That time I got reincarnated as a","created":"2021-09-15 06:28:08","category_id":"0","category_name":null}]}

Read All Article - https://creatordesk.otamyanmar.com/article/read.php
Example respond - 
{"articles":[{"art_id":"1","art_title":"MindaRyn : The girl whose dream came true","art_thumb":"https:\/\/creatordesk.otamyanmar.com\/\/static\/lightnovel\/avatars-000309892720-6f2gl0-t500x500.jpg","art_sum":"anime song \u1010\u103d\u1031 cover \u1006\u102d\u102f\u1010\u1032\u1037 \u1011\u102d\u102f\u1004\u103a\u1038 \u1014\u102d\u102f\u1004\u103a\u1004\u1036\u1000 \u1021\u1006\u102d\u102f\u1010\u1031\u102c\u103a\/you tuber \u1000\u1031\u102c\u1004\u103a\u1019\u101c\u1031\u1038 MindaRyn \u1000 \u1014\u102c\u1019\u100a\u103a\u1000\u103c\u102e\u1038 anime \u1016\u103c\u1005\u103a\u1010\u1032\u1037 That time I got reincarnated as a","created":"2021-09-15 06:28:08","category_id":"0","category_name":null}]}


Search article      - https://creatordesk.otamyanmar.com/article/search.php?s= 'key word'

Read Article content - http://creatordesk.otamyanmar.com/article/readone.php?art_id= 'id' 
Example respond - {"cont":[{"arcon_id":"10","art_id":"1","arcon_num":"0","arcon_type":"","arcon_body":"<p>\u1014\u102c\u1019\u100a\u103a\u1000\u103c\u102e\u1038 isekai anime..."}]}
  
Read article Info - http://creatordesk.otamyanmar.com/article/readinfo.php?art_id= 'id'
Example respond - {"art_id":"1","art_title":"MindaRyn : The girl whose dream came true","art_thumb":"https:\/\/creatordesk.otamyanmar.com\/\/static\/lightnovel\/avatars-000309892720-6f2gl0-t500x500.jpg","art_sum":"anime song \u1010\u103d\u1031 cover \u1006\u102d\u102f\u1010\u1032\u1037 \u1011\u102d\u102f\u1004\u103a\u1038 \u1014\u102d\u102f\u1004\u103a\u1004\u1036\u1000 \u1021\u1006\u102d\u102f\u1010\u1031\u102c\u103a\/you tuber \u1000\u1031\u102c\u1004\u103a\u1019\u101c\u1031\u1038 MindaRyn \u1000 \u1014\u102c\u1019\u100a\u103a\u1000\u103c\u102e\u1038 anime \u1016\u103c\u1005\u103a\u1010\u1032\u1037 That time I got reincarnated as a","created":"2021-09-15 06:28:08","category_id":"0","category_name":null}
  
Light Novel 

Read Recent Light Novel -   https://creatordesk.otamyanmar.com/lightnovel/readtip.php
Read All Light Novel    -   https://creatordesk.otamyanmar.com/lightnovel/read.php
Search Light Novel      - https://creatordesk.otamyanmar.com/lightnovel/search.php?s= 'key word'  
Read one Light Novel    -  https://creatordesk.otamyanmar.com/lightnovel/readone.php?lightnovel_id= 'id'
Read Light Novel Chapters - https://creatordesk.otamyanmar.com/lightnovel/read_Chpt.php?lightnovel_id= 'id'
Read Chpt contents      - https://creatordesk.otamyanmar.com/lightnovel/readnvcontent.php?chpt_id='id'  
  
