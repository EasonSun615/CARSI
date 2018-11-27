carsi
===
> carsi_member
>> * index
>> * type
>> * name
>> * dns
>> * department
>> * country
>> * province
>> * city
>> * address
>> * [logo](#carsi---logo)
>> * mgr_bus_name >> mgr_bus_tel >> mgr_bus_phone >> mgr_bus_email
>> * opr_tech_name >> opr_tech_tel >> opr_tech_phone >> opr_tech_email
>> * idp_dns
>> * idp_contract??
>> * eduGAIN
>> * status
>> * imestamp

> sp_info
>> * sp_id
>> * member_index
>> * sp_name
>> * sp_description
>> * sp_url
>> * [sp_step_file](#sp_info---step_file)
>> * [sp_metadata_file](#sp_info---sp_metadata_file)
>> * sp_idp_contract


## Details

### carsi - logo
存*file* ，路径是 backend/web/member_file/%dns%/%dns%_%logo%.jpg

### sp_info - step_file
存*file* ，路径是 backend/web/member_file/%dns%/%dns%_step\[.pdf/.txt\]

### sp_info - sp_metadata_file
存*file* ，路径是 backend/web/member_file/%dns%/%dns%_metadata\[.xml/.txt\]
