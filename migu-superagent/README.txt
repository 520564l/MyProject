���ֽӿ�����:

[��������]
localhost:3000/music/playMusic/musicId	
��:
localhost:3000/music/playMusic/10052 


[��ʼ��ȡ,ֱ�ӵ����޲���,������ȡ��ɵĸ����б�]
localhost:3000/migu/beginMusics


[���������ݿ���������� post��ʽ]
localhost:3000/song/addMusics

��:
{
	
   "musics":[
	{
"musicId":"11110532314",
"musicName":"���������",
"songSinger":"ׯ����",
"songCover": "http://cdn.music.migu.cn/picture/2018/0913/1421/AM��"}
    ]

}



������ʽ:

 cd migu-superagent
 
 npm install 

 npm start

�״�������ʱ����Ҫ��mysql-db.js����������,���Ƚ������ݿ�,���� music.sql

�ļ��h����
	

superagent/migu-superagent.js �����ļ�

mysql-db.js	���ݿ����ӳع���

migu.js //����·��

music.js //�����ļ�·��