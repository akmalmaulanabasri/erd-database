#Test
Generated using [DbSchema](https://dbschema.com)




### Main Layout
![img](./MainLayout.svg)



### Table public.piutang_barang 
|Idx |Name |Data Type |
|---|---|---|
| * &#128269; &#11016; | user\_id| varchar  |
|  | nama\_barang| varchar  |
|  | quantity| integer  |
|  | harga| integer  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128269;  | user\_id | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_piutang_barang_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.piutang_jasa 
|Idx |Name |Data Type |
|---|---|---|
| * &#128269; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128269;  | unq\_piutang\_jasa\_user\_id | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_piutang_jasa_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.piutang_uang 
|Idx |Name |Data Type |
|---|---|---|
| * &#128269; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128269;  | unq\_piutang\_uang | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_piutang_uang_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_piutang_barang 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_4 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_4 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_piutang_jasa 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_6 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_6 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_piutang_uang 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_5 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_5 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_simpanan_khusus 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_2 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_2 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_simpanan_pokok 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_3 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_3 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_simpanan_sukarela 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_1 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_1 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.riwayat_simpanan_wajib 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib\_0 | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users_0 | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.simpanan_khusus 
|Idx |Name |Data Type |
|---|---|---|
| * &#128269; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128269;  | unq\_simpanan\_khusus | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_khusus_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.simpanan_pokok 
|Idx |Name |Data Type |
|---|---|---|
| * &#128269; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128269;  | unq\_simpanan\_pokok | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_pokok_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.simpanan_sukarela 
|Idx |Name |Data Type |
|---|---|---|
| * &#128269; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128269;  | unq\_simpanan\_sukarela | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_sukarela_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.simpanan_wajib 
|Idx |Name |Data Type |
|---|---|---|
| * &#128270; &#11016; | user\_id| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128270;  | idx\_simpanan\_wajib | ON user\_id|

##### Foreign Keys
|Type |Name |On |
|---|---|---|
|  | fk_simpanan_wajib_users | ( user\_id ) ref [public.users](#users) (user\_id) |




### Table public.users 
|Idx |Name |Data Type |
|---|---|---|
| * &#128273;  &#11019; | user\_id| varchar  |
| * | name| varchar  |
| * | email| varchar  |
|  | address| varchar  |
| * &#128269; | phone\_num| varchar  |
| * &#128269; | gender| varchar  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128273;  | pk\_users | ON user\_id|
| &#128269;  | unq\_users\_phone\_num | ON phone\_num|
| &#128269;  | unq\_users\_gender | ON gender|




