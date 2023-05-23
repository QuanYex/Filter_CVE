# Filter_CVE
日常运营可能有些扫描器扫到一堆问题，需要人为过滤（查阿里云漏洞库），写个小脚本过滤漏洞.

同文件夹下建立两个excel表(漏洞信息报表.xlsx、cve_res.xlsx）

具体过滤的可以根据这里改，可以改成武器化等，根据ali漏洞库字段来自行修改
tag_with_title_exp = soup.find('button', {'title': '暂无可利用代码'})
        if tag_with_title_exp:
            continue
        else:
            CVE_res.append(CVE_Num)
            print(CVE_res)
