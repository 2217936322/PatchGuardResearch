# win10 PatchGuard ��̬����(btc�汾)  

**����Ŀ�ܹ���̬����pgContext��һ����**  
pgContext���ɶ���������    
0 - 0xc8��һ����    
0 - RtlMinimalBarrier��ƫ����һ����(��1803��,��ƫ��Ϊ0x1A2A8)    
RtlMinimalBarrier - RtlMinimalBarrier+0xA00 ������    
0x1A2A8+0xA00 - ....����һ�����ܵ�Context    
������Կ�doc�е�dump.log    
����Ŀ����0 - RtlMinimalBarrier��ƫ��    
���ڹ���PatchGuard,���ƫ���е������Ѿ��㹻    

## ԭ��

��ͨ���۲�dump.log�Ѿ����0x109�������ļ�,���Եó�һ����Ϣ    
��c8~RtlMinimalBarrier�����ݽ�β������retΪ��β    
��retΪRtlMinimalBarrier����β������    

![pg](https://github.com/zhuhuibeishadiao/PatchGuardResearch/blob/master/doc/pg.PNG)    
��������ͨ��pgContext��ǰ4�����������ڴ���ײ���õ�pgContext���׵�ַ(ע��,��1809 rs5�汾��,rcx��ֵ�ı���)    
�����ϸ�ڴ�ȫ����ɺ����.    

## ����Ŀ�ݲ�����PatchGuard    
��ʵ,���˽���֮�����Ѿ�����������.    
ֻ��Ŀǰ���Ĳ����ڹ���,����.  

## Ŀ¼˵��  
doc:һЩ��������  
helper:���ڸ���dump��У��pgContext  
PatchGuard:���߼�  

## ��л
[tandasat : some-tips-to-analyze-patchguard](http://standa-note.blogspot.com/2015/10/some-tips-to-analyze-patchguard.html)  
[tandasat : findpg](https://github.com/tandasat/findpg)  
[tandasat : PgResarch](https://github.com/tandasat/PgResarch)  
[mengwuji : windows10 patchguard�ƹ�����]    
[mengwuji : �ƹ�windows10 patchguardԭ����ʵ��]    
[9176324 : Shark](https://github.com/9176324/Shark)  
[DarthTon : Blackbone](https://github.com/DarthTon/Blackbone)    
[Mr Guo]    


