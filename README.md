\#include<stdio.h>



int main() {

&nbsp;	int s = 1;

&nbsp;	int t;

&nbsp;	char y\_n;

&nbsp;	char pokemon;

&nbsp;	printf("ポケモン当てクイズ(サトシ)\\n");

&nbsp;	printf("あなたの考えているカントー地方の時にサトシと出会ったポケモンは？\\n");



&nbsp;	printf("そのポケモンのタイプは？\\n(ノーマル：０、かくとう：１、どく：２、じめん：３、ひこう：４、むし：５、いわ：６、ゴースト：７、はがね：８、ほのお：９、みず：１０、でんき：１１、くさ：１２、こおり：１３、エスパー：１４、ドラゴン：１５、あく：１６、フェアリー：１７)");

&nbsp;	scanf("%d", \&t);



&nbsp;	//第一世代（ノーマル）

&nbsp;	if (s == 1) {

&nbsp;		if (t == 0) {

&nbsp;			printf("そのポケモンは進化をしますか？(y/n)>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'y') {

&nbsp;				printf("そのポケモンはピジョンですか？(y/n)>>");

&nbsp;				scanf(" %c", \&pokemon);

&nbsp;				if (pokemon == 'y') {

&nbsp;					printf("私の勝ち");

&nbsp;				}

&nbsp;				else if (pokemon == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'n') {

&nbsp;				printf("そのポケモンは空を飛びますか（y/n）>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはピジョットですか(y/n)>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("私の勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("そのポケモンはたくさんゲットされましたか？（y/n）>>");

&nbsp;					scanf(" %c", \&y\_n);

&nbsp;					if (y\_n == 'y') {

&nbsp;						printf("そのポケモンはケンタロスですか？(y/n)>>");

&nbsp;						scanf(" %c", \&pokemon);

&nbsp;						if (pokemon == 'y') {

&nbsp;							printf("私の勝ち");

&nbsp;						}

&nbsp;						else if (pokemon == 'n') {

&nbsp;							printf("私の負け");

&nbsp;						}

&nbsp;						else {

&nbsp;							printf("どっちなんだい");

&nbsp;						}

&nbsp;					}

&nbsp;					else if (y\_n == 'n') {

&nbsp;						printf("そのポケモンは大食いですか？(y/n)>>");

&nbsp;						scanf(" %c", \&y\_n);

&nbsp;						if (y\_n == 'y') {

&nbsp;							printf("そのポケモンはカビゴンですか？(y/n)>>");

&nbsp;							scanf(" %c", \&pokemon);

&nbsp;							if (pokemon == 'y') {

&nbsp;								printf("私の勝ち");

&nbsp;							}

&nbsp;							else if (pokemon == 'n') {

&nbsp;								printf("私の負け");

&nbsp;							}

&nbsp;							else {

&nbsp;								printf("どっちなんだい");

&nbsp;							}

&nbsp;						}

&nbsp;						else if (y\_n == 'n') {

&nbsp;							printf("そのポケモンはラッタですか？(y/n)>>");

&nbsp;							scanf(" %c", \&pokemon);

&nbsp;							if (pokemon == 'y') {

&nbsp;								printf("私の勝ち");

&nbsp;							}

&nbsp;							else if (pokemon == 'n') {

&nbsp;								printf("私の負け");

&nbsp;							}

&nbsp;						}

&nbsp;						else {

&nbsp;							printf("どっちなんだい");

&nbsp;						}

&nbsp;					}



&nbsp;				}

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どれなんだい");



&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（かくとう）

&nbsp;		else if (t == 1) {

&nbsp;			printf("そのポケモンは進化しますか？(y/n)>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'y') {

&nbsp;				printf("そのポケモンはマンキーですか？(y/n)>>");

&nbsp;				scanf(" %c", \&pokemon);

&nbsp;				if (pokemon == 'y') {

&nbsp;					printf("私の勝ち");

&nbsp;				}

&nbsp;				else if (pokemon == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'n') {

&nbsp;				printf("そのポケモンはオコリザルですか？(y/n)");

&nbsp;				scanf(" %c", \&pokemon);

&nbsp;				if (pokemon == 'y') {

&nbsp;					printf("私の勝ち");

&nbsp;				}

&nbsp;				else if (pokemon == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（毒）

&nbsp;		else if (t == 2) {

&nbsp;			printf("そのポケモンは進化しますか（y/n）>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'n') {

&nbsp;				printf("そのポケモンはベトベトンですか？(y/n)>>");

&nbsp;				scanf(" %c", \&pokemon);

&nbsp;				if (pokemon == 'y') {

&nbsp;					printf("私の勝ち");

&nbsp;				}

&nbsp;				else if (pokemon == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'y') {

&nbsp;				printf("そのポケモンは草タイプでもありますか？(y/n)>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはフシギダネですか？(y/n)>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("私の勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("そのポケモンはゴーストですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("私の勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（じめん）

&nbsp;		else if (t == 3) {

&nbsp;			printf("そんなポケモンいたかな？");

&nbsp;		}



&nbsp;		//第一世代（ひこう）

&nbsp;		else if (t == 4) {

&nbsp;			printf("そのポケモンは進化しますか（y/n）>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'y') {

&nbsp;				printf("そのポケモンはピジョンですか(y/n)>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("私の勝ち");

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'n') {

&nbsp;				printf("そのポケモンは虫タイプですか？(y/n)>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはバタフリーですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("私の勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("そのポケモンはノーマルタイプですか（y/n）>>");

&nbsp;					scanf(" %c", \&y\_n);

&nbsp;					if (y\_n == 'y') {

&nbsp;						printf("そのポケモンはピジョットですか？（y/n）>>");

&nbsp;						scanf(" %c", \&pokemon);

&nbsp;						if (pokemon == 'y') {

&nbsp;							printf("私の勝ち");

&nbsp;						}

&nbsp;						else if (pokemon == 'n') {

&nbsp;							printf("わたしの負け");

&nbsp;						}

&nbsp;						else {

&nbsp;							printf("どっちなんだい");

&nbsp;						}

&nbsp;					}

&nbsp;					else if (y\_n == 'n') {

&nbsp;						printf("そのポケモンはリザードンですか（y/n）>>");

&nbsp;						scanf(" %c", \&pokemon);

&nbsp;						if (pokemon == 'y') {

&nbsp;							printf("私の勝ち");

&nbsp;						}

&nbsp;						else if (pokemon == 'n') {

&nbsp;							printf("私の負け");

&nbsp;						}

&nbsp;						else {

&nbsp;							printf("どっちなんだい");

&nbsp;						}



&nbsp;					}





&nbsp;				}

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（むし）

&nbsp;		else if (t == 5) {

&nbsp;			printf("そのポケモンは進化しますか（y/n）>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'n') {

&nbsp;				printf("そのポケモンはバタフリーですか（y/n）>>");

&nbsp;				scanf(" %c", \&pokemon);

&nbsp;				if (pokemon == 'y') {

&nbsp;					printf("わたしの勝ち");

&nbsp;				}

&nbsp;				else if (pokemon == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'y') {

&nbsp;				printf("そのポケモンは二回進化しますか（y/n）>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはキャタピーですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんかい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("そのポケモンはトランセルですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんかい");

&nbsp;					}

&nbsp;				}

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（いわ）

&nbsp;		else if (t == 6) {

&nbsp;			printf("そんなポケモンいたかな");

&nbsp;		}



&nbsp;		//第一世代（ゴースト）

&nbsp;		else if (t == 7) {

&nbsp;			printf("そのポケモンはゴーストですか（y/n）>>");

&nbsp;			scanf(" %c", \&pokemon);

&nbsp;			if (pokemon == 'y') {

&nbsp;				printf("私の勝ち");

&nbsp;			}

&nbsp;			else if (pokemon == 'n') {

&nbsp;				printf("私の負け");

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どっちなんだい");

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（はがね）

&nbsp;		else if (t == 8) {

&nbsp;			printf("そんなポケモンいたかな");

&nbsp;		}



&nbsp;		//第一世代（ほのお）

&nbsp;		else if (t == 9) {

&nbsp;			printf("そのポケモンは進化しますか（y/n）>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'n') {

&nbsp;				printf("そのポケモンはリザードンですか（y/n）>>");

&nbsp;				scanf(" %c", \&pokemon);

&nbsp;				if (pokemon == 'y') {

&nbsp;					printf("わたしの勝ち");

&nbsp;				}

&nbsp;				else if (pokemon == 'n') {

&nbsp;					printf("私の負け");

&nbsp;				}

&nbsp;				else {

&nbsp;					printf("どっちなんだい");

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'y') {

&nbsp;				printf("そのポケモンは反抗期でしたか？(y/n)>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'n') {

&nbsp;					printf("そのポケモンはヒトカゲですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはリザードですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（みず）

&nbsp;		else if (t == 10) {

&nbsp;			printf("そのポケモンは進化しますか（y/n）>>");

&nbsp;			scanf(" %c", \&y\_n);

&nbsp;			if (y\_n == 'y') {

&nbsp;				printf("そのポケモンは二回進化しますか（y/n）>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはゼニガメですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("そのポケモンはクラブですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;			}

&nbsp;			else if (y\_n == 'n') {

&nbsp;				printf("そのポケモンは氷タイプですか(y/n)>>");

&nbsp;				scanf(" %c", \&y\_n);

&nbsp;				if (y\_n == 'y') {

&nbsp;					printf("そのポケモンはラプラスですか(y/n)>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;				else if (y\_n == 'n') {

&nbsp;					printf("キングラーですか（y/n）>>");

&nbsp;					scanf(" %c", \&pokemon);

&nbsp;					if (pokemon == 'y') {

&nbsp;						printf("わたしの勝ち");

&nbsp;					}

&nbsp;					else if (pokemon == 'n') {

&nbsp;						printf("私の負け");

&nbsp;					}

&nbsp;					else {

&nbsp;						printf("どっちなんだい");

&nbsp;					}

&nbsp;				}

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（でんき）

&nbsp;		else if (t == 11) {

&nbsp;			printf("そのポケモンはピカチュウですか（y/n）>>");

&nbsp;			scanf(" %c", \&pokemon);

&nbsp;			if (pokemon == 'y') {

&nbsp;				printf("わたしの勝ち");

&nbsp;			}

&nbsp;			else if (pokemon == 'n') {

&nbsp;				printf("私の負け");

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どっちなんだい");

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（くさ）

&nbsp;		else if (t == 12) {

&nbsp;			printf("そのポケモンはフシギダネですか(y/n)>>");

&nbsp;			scanf(" %c", \&pokemon);

&nbsp;			if (pokemon == 'y') {

&nbsp;				printf("わたしの勝ち");

&nbsp;			}

&nbsp;			else if (pokemon == 'n') {

&nbsp;				printf("私の負け");

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どっちなんだい");

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（こおり）

&nbsp;		else if (t == 13) {

&nbsp;			printf("そのポケモンはラプラスですか（y/n）>>");

&nbsp;			scanf(" %c", \&pokemon);

&nbsp;			if (pokemon == 'y') {

&nbsp;				printf("わたしの勝ち");

&nbsp;			}

&nbsp;			else if (pokemon == 'n') {

&nbsp;				printf("私の負け");

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どっちなんだい");

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（エスパー）

&nbsp;		else if (t == 14) {

&nbsp;			printf("そのポケモンはバリヤードですか（y/n）>>");

&nbsp;			scanf(" %c", \&pokemon);

&nbsp;			if (pokemon == 'y') {

&nbsp;				printf("わたしの勝ち");

&nbsp;			}

&nbsp;			else if (pokemon == 'n') {

&nbsp;				printf("私の負け");

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どっちなんだい");

&nbsp;			}

&nbsp;		}



&nbsp;		//第一世代（ドラゴン）

&nbsp;		else if (t == 15) {

&nbsp;			printf("そんなポケモンいあたかな？");

&nbsp;		}



&nbsp;		//第一世代（あく）

&nbsp;		else if (t == 16) {

&nbsp;			printf("そんなポケモンいたかな？");

&nbsp;		}



&nbsp;		//第一世代（フェアリー）

&nbsp;		else if (t == 17) {

&nbsp;			printf("そのポケモンはバリヤードですか（y/n）>>");

&nbsp;			scanf(" %c", \&pokemon);

&nbsp;			if (pokemon == 'y') {

&nbsp;				printf("わたしの勝ち");

&nbsp;			}

&nbsp;			else if (pokemon == 'n') {

&nbsp;				printf("私の負け");

&nbsp;			}

&nbsp;			else {

&nbsp;				printf("どっちなんだい");

&nbsp;			}

&nbsp;		}

&nbsp;	}return 0;

}

