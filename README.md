# ChainManAPI  

/get_coins  
    获取所有币种代码更新信息  
    params: commit_num (可选, int, 默认10)  
    return: 错误  {'code': '1010', 'msg': 'get coins error'}  
            成功  {  
                  "BitShares": [  
                    {  
                      "additions": 3771,  
                      "author": "Abit",  
                      "coin": "BitShares",  
                      "collect_time": "Wed, 11 Apr 2018 01:24:26 GMT",  
                      "commit_sha": "92eb45cbd3e61c163561b0e6cf7fc99c633e4fcf",  
                      "commit_time": "Thu, 29 Mar 2018 03:07:53 GMT",  
                      "committer": "GitHub",  
                      "content": null,  
                      "create_time": "Thu, 29 Mar 2018 03:07:53 GMT",  
                      "deletions": 1074,  
                      "html_url": "https://github.com/bitshares/bitshares-core/commit/92eb45cbd3e61c163561b0e6cf7fc99c633e4fcf",  
                      "repo_name": "bitshares/bitshares-core",  
                      "total": 4845  
                    },  
                    {  
                    },  
                    ......  
                  ],  
                  "Bitcoin": [  
                    ......  
                  ],  
                  ......  
                 }  
				 