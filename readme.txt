1.git config --global user.email "151812117@qq.com"
2.git config --global user.name "rc"
3.cd c:\cr
   mkdir repo
   cd repo
4.git add readme.txt
5.git commit -m "create a new readme"
   ���أ�c:\CR\repo>git commit -m "create a new readme"
             [master (root-commit) f3982d9] create a new readme
             1 file changed, 1 insertion(+)
             create mode 100644 readme.txt
6.git status:�鿴��������״̬�����������ļ����޸Ĺ�����git diff���Բ鿴�޸�����
7.�汾���ˣ�HEADָ��İ汾���ǵ�ǰ�汾��HEAD~n��ʾ��ǰ�汾��ǰn���汾����ˣ�Git���������ڰ汾����ʷ֮�䴩��ʹ������git reset --hard commit_id
   ��git log���Բ鿴�ύ��ʷ���Ա�ȷ��Ҫ���˵��ĸ��汾��
   ��git reflog�鿴������ʷ���Ա�ȷ��Ҫ�ص�δ�����ĸ��汾��
8.conflict