# ʵ�ú�����
## PasswordFunction.php
��php5.3��php5.4�汾��**ʵ��php5.5�������ϰ汾�е����õ�Bcrypt����������**

**password_hash()**

**password_get_info()**

**password_verify()**

**password_needs_rehash()**

**���**��<a href="http://cn2.php.net/manual/zh/ref.password.php" target=_blank>http://cn2.php.net/manual/zh/ref.password.php</a>
## FilterValidFunction.php
����ַ����Ƿ��������Ҫ��Ķ������������

**�����ַ=>bool is_mail_valid(string $mail)**

**�쳯�ֻ���=>bool is_phone_valid(mixed $phone)**

**http��https��ͷ��Url=>bool is_url_valid(string $url)**

**����ID�˻�=>bool is_uid_valid(mixed $uid,int $minLength[=4],int $maxLength[=11])**

������������һ����ѡ����$uidΪ��Ҫ��������ID���ڶ�����ѡ����$minLengthָ���Ϸ���uid���λ��[Ĭ��4λ]����������ѡ����$maxLengthָ���Ϸ���uid���λ��[Ĭ��11λ]

**[����Ҫͬʱ�������ֺ���ĸ��]�����ʽЧ��=>bool is_password_valid(string $password,int $minLength[=8],int $maxLength[=16])**

������������һ����ѡ����$passwordΪ��Ҫ���������ַ������ڶ�����ѡ����$minLengthָ���Ϸ��������ַ�����С����[Ĭ��8���ַ���]����������ѡ����$maxLengthָ���Ϸ��ĺϷ��������ַ�����󳤶�[Ĭ��16���ַ���]

**�쳯���֤��=>mixed is_citizen_id_valid(mixed $citizen_id)**

�������ͣ�false����array������ȫ�Ƿ���boolean���ͣ������ص�array��һ����������[���Դ���ȡֵ]�������ж�Ϊtrue���ú�������15λ�����֤�ź�18λ�����֤��[������15λ�Ϸ������֤�Ž�����ת������18λ���֤��]

## UsefullFunction.php
��װ��һЩ���õķ�����

**ʱ��ת��Ϊ�Ѻ���ʾ�������硰5����ǰ��=>string time_ago(int $UnixTimeStamp)**

**�ļ�����ֽڣ�Byte��ת��Ϊ�Ѻñ�ʾ�������硰5MB��=>string format_bytes($size, $delimiter = '')**