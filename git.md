#Gitʹ��#

###��������Working Directory��###
���ص������ܿ�����Ŀ¼�������ҵ�mygitrepo�ļ��о���һ����������
###�汾�⣨Repository��###
��������һ������Ŀ¼.git������Git�İ汾�⡣

##��ʼ�����ؿ�##
    mkdir reponame
    cd reponame
    git init

##�ļ������ύ##
    git add myfile.txt
    git commit -m "add file"

##Զ�ֿ̲�##
*  ���Զ�ֿ̲�  
   `git remote add origin git@github.com:username/reponame.git`  
   Զ�̿�����־���origin������GitĬ�ϵĽз���Ҳ���Ըĳɱ�ģ�����origin�������һ����֪����Զ�̿⡣

*  ���ͱ������ݵ�Զ�̿�  
   `git push -u origin master`  
   �ѱ��ؿ���������͵�Զ�ˣ���git push���ʵ�����ǰѵ�ǰ��֧master���͵�Զ�̡�

*  Զ�ֿ̲�clone  
   `git clone https://github.com/plusjade/jekyll-bootstrap.git`
   
##ɾ���ļ�##
    rm myfile.txt
    git rm myfile.txt
	
##�ָ�ɾ�����ļ�##
    git checkout -- recoverfilename  
    **ֻ�ָܻ�rm����ɾ�����ļ���git rm����ִ���Ժ��ļ��޷��ָ�**



