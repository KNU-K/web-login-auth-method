## using cookie

cookie login ����� res.cookie�� ��� user���� �ִ� ���·� ���� �Ǵ´�. �׸��� user ������ ������ ������ ���� �ǰ� �ϴ� ��Ŀ������ ��� �ִ�.

- cookie �� httponly ���� ���� �ɼ����� ���ȼ��� ������ �� �ִ�.

- Ŭ���̾�Ʈ���� �������� �����ϱ� ������, ���ȼ����� ����ϴ�.

## using session

session login ����� req.session �� ��� ������ �⺻������ �������� session�� �����ϰ� �˴ϴ�. �׸��� user �� session ������ credential �ɼ����� ������ �ϰ� �Ǹ� ���������� �α��λ��¸� ������ �� �ֽ��ϴ�.

- user�� ��� ������ �ƴ� pk(primary key) ������ �ֱ� ������, deserialize �� ���ļ� ��ü������ req.user �� ������ �̵����� ��ȯ ��Ŵ���μ�, ���ȼ� ������ �����ϴ�.

- ���� ����ڰ� api �� ������ ������ ���¸� ������Ʈ���ִ� �̵��� �����ν�, ������� ���¸� ������ �� �ִ�. �̴� ��Ȱ�� �ñ��� ����ڿ��� �ڵ� �α׾ƿ��� �ǵ��� �� �� �ִ�.

- session�� ���ᰪ�� ���� �����ؾ��ϰ�, ������ �ڿ��� ����ϱ� ������ cookie �α��ο� ���ؼ� ��������, �ݴ�� ���ȼ��� cookie ���� �� ���� �� �ȴ�.