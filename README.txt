IDDD���ĸ�����Ŀ��ɣ�

1.iddd_agilepm ��Ŀ��һ����LevelDB����key-value�洢��Ϊ�־ò�İ�����
    LevelDB ��һ����Javaʵ��: https://github.com/dain/leveldb
    iddd_agilepm��û��ʹ���κ�����(such as Spring).

2.iddd_collaboration��Ŀ��һ��ʹ�� Event Sourcing ��
CQRS�İ���.������ʹ����ORM֮���ܣ�չʾ����JDBC�Ĳ�ѯ����.
    ����������Ȼ��������ԣ�������ζ��С���죬�����κ�Ԫע��֮�����ã���Ȼ��������
  iddd_collaboration��Ŀչʾ���־�Event Sourcedдģ�ͺ�������һ���߳�ʵ��CQRS�Ķ�ģ��.
    ʹ��LevelDB�����¼��洢���Ŷ� MySQL���ڶ�ģ�͵Ĵ洢��Ҳ������֮����Щ���ݲ�һ�£���ʵ������һ���ԡ�

3.The iddd_identityaccess ��Ŀ��ʹ��ORM��Ϊ�־�(Hibernate),
    ����Ҳû�б������ţ��ṩһ��RESTful�ͻ��˽ӿڣ�ͨ��REST (logs)
    �� RabbitMQ.�ɷ���Domain-Event���ѡ�

4.iddd_common ��Ŀ�ṩ���������������Ȼ������ͼ��Ϊһ����ܣ���������ߴ������á�