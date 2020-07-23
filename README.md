### 參考來源
- [github](https://github.com/osixia/docker-openldap)
- [實作 Kubernetes 外部認證系統整合: 以 LDAP 為例](https://k2r2bai.com/2019/09/29/ironman2020/day14/)  



- login 教學
  - admin
    - Login DN：cn=admin,dc=lab,dc=com,dc=tw
    - Password：password
  - config
    - Login DN：cn=admin,cn=config
    - Password：password

### 筆記
- CN (Common Name)
- OU (Organizational Unit)
- DC (Domain Component)

- 若有個domain 叫做`lab.com.tw`,有個OU叫做school,OU school下有個user叫做andy.huang則 完整表示該user的方式叫做DN
  - DN表示式是由小到大,若要表示andy.huang這個user的DN就是`cn=andy.huang,ou=school,dc=lab,dc=com,dc=tw`
