\#include<stdio.h>

int main() {

&nbsp;	int sedai,taipu,sinnka,pokemonn,live;

&nbsp;	printf("サトシのポケモンを考えてください");

&nbsp;	printf("そのポケモンの世代はいつですか？\\n第一世代なら1、第二世代なら2…新無印なら8を選択してください。");

&nbsp;	scanf("%d", \&sedai);

&nbsp;	switch (sedai) {

&nbsp;	case 1://第一世代（カントー）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {

&nbsp;			pirntf("そのポケモンは進化しますか？\\nyesなら1、noなら0を>>");

&nbsp;			scanf("%d", \&sinnka);

&nbsp;			if (sinnka == 1) {

&nbsp;				printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;				scanf("%d", \&taipu);

&nbsp;				if (taipu == 1) {

&nbsp;					printf("そのポケモンはピジョンですか？\\nyesなら1、noなら0を>>");

&nbsp;					scanf("%d", \&pokemonn);

&nbsp;					if(pokemonn==1){

&nbsp;						printf("私の勝ち");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;				}				

&nbsp;			}

&nbsp;			printf("そのポケモンはたくさんGETしましたか？\\nyesなら1、noなら0を>>");

&nbsp;			scanf("%d", \&get);

&nbsp;			if (get == 1) {

&nbsp;				printf("そのポケモンはケンタロスですか？\\nyesなら1、noなら0を>>");

&nbsp;				scanf("%d", \&pokemonn);

&nbsp;				if (pokemonn == 1) {

&nbsp;					printf("私の勝ち");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				printf("そのポケモンは長い期間サトシといましたか？\\nyesなら1、noなら0を>>");

&nbsp;				scanf("%d",\&live)						}

&nbsp;						if(live==0){

&nbsp;							printf("ならラッタですか？\\nyesなら1、noなら0を>>")

&nbsp;								scanf("%d", \&pokemonn);

&nbsp;							if (pokemonn == 1) {

&nbsp;								printf("私の勝ち");

&nbsp;							}

&nbsp;							else {

&nbsp;								printf("私の負け");

&nbsp;							};

&nbsp;						}

&nbsp;					else {

&nbsp;						printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;						scanf("%d", \&taipu);

&nbsp;						if (taipu == 1) {

&nbsp;							printf("そのポケモンはピジョットですか？\\nyesなら1、noなら0を>>");

&nbsp;							scanf("%d", \&pokemonn);

&nbsp;							if (pokemonn == 1) {

&nbsp;								printf("私の勝ち");

&nbsp;							}

&nbsp;							else {

&nbsp;								printf("私の負け");

&nbsp;							}

&nbsp;						}

&nbsp;						printf("そのポケモンはカビゴンですか？\\nyesなら1、noなら0を>>");

&nbsp;						scanf("%d", \&pokemonn);

&nbsp;						if (pokemonn == 1) {

&nbsp;							printf("私の勝ち");

&nbsp;						}

&nbsp;						else {

&nbsp;							printf("私の負け");

&nbsp;						}

&nbsp;					}

&nbsp;			}

&nbsp;		

&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {

&nbsp;		

&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {

&nbsp;		

&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;

&nbsp;	}

&nbsp;	case 2: {//第二世代（ジョウト）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;

&nbsp;	

&nbsp;	}

&nbsp;	case 3: {//第三世代（ホウエン）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;

&nbsp;	}

&nbsp;	case 4: {//第四世代（シンオウ）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;

&nbsp;	}

&nbsp;	case 5: {//第五世代（イッシュ）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;

&nbsp;	

&nbsp;	}

&nbsp;	case 6: {//第六世代（カロス）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;

&nbsp;	

&nbsp;	}

&nbsp;	case 7: {//第七世代（アローラ）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}break;



&nbsp;	}

&nbsp;	case 8: {//第八世代（新無印）

&nbsp;		printf("そのポケモンはノーマルタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1) {



&nbsp;		}printf("そのポケモンは格闘タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは毒タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは地面タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは飛行タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは虫タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは岩タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはゴーストタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは鋼タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは炎タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは水タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは電気タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは草タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは氷タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはエスパータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはドラゴンタイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンは悪タイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}

&nbsp;		printf("そのポケモンはフェアリータイプですか？\\nyesなら1、noなら0を>>");

&nbsp;		scanf("%d", \&taipu);

&nbsp;		if (taipu == 1); {



&nbsp;		}



&nbsp;	}break;

}

