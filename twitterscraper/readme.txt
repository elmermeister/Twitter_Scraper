1.�b���|�� �}�� cmd �H�U�O�ڪ��q���� �C�ӤH�����P
C:\Users\Elmer\Desktop\twitterscraper-master\twitterscraper
2.�����Q�n����� �bcmd�����W

twitterscraper "X AND pregnant" --lang=en --limit 3000 -o tweets.json

X��WORD��������r �H�U�Hpain-medicine����

twitterscraper "Pain-medicine AND pregnant" --lang=en --limit 3000 -o tweets.json


3.�q json�নcsv 
�]������ ��Ƨ����|����tweet.json��
�ɮפj�p���@ �h�ƤW����3000�h

�bcmd�����W 
python json_to_csv.py 
��Ƨ����|�A�X�{�@�� tweet.csv��

4.���ƦW�٤@�ߧ令 
tweet_X.json
tweet_X.csv
�æs��b�U�۪���Ƨ���


ps . 
1.����ǹq��3000�h�]�U�Ӭ���50�� 
2.�j�p�g������Ƥ@�� ex : Vitamin ,vitamin
3.���S�� '-' �S���t�O ���_�Ӹ�ƨ̼�ex :anti-anxiety-meds ,anti anxiety meds 