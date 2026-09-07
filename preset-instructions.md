# Preset Instructions

## SQLAlchemy URL
```
snowflake://preset@onvdtav-ft81429/AIRBNB?role=REPORTER&warehouse=COMPUTE_WH
```

## Security JSON
```json
{
    "auth_method": "keypair",
    "auth_params": {
        "privatekey_body": "-----BEGIN ENCRYPTED PRIVATE KEY-----\nMIIFNTBfBgkqhkiG9w0BBQ0wUjAxBgkqhkiG9w0BBQwwJAQQJaOgnAUDy7wh7Tz2\nK8R1aAICCAAwDAYIKoZIhvcNAgkFADAdBglghkgBZQMEASoEEAHnqHDvFUpBJGra\nT4uvCtcEggTQ0elOIF6AhyqjvLa43yxzbHvvxbELtgBT58Mrx28qdzuHI2/oM3jx\nzz+JWDatKgME6jjfgpwWfamgONczzAWBs4IkIcGZJ3WvnIh5lhcC7TZ4qAXBxVTR\nGb92YWzZsLFB6UFEo2a17ZkVdBR0mz6LuIlcAARxaknUvL8v7rBRrHbycIObzqDO\n67wq2yJ+a5YEG54x3iS/5El3CdnmR3UxO8/Cnvs1EoE79fnifmcUqCbX2DZv7gP7\nS376B5jZQSY9MHD5lBH/vgy5h4wVfS+8Xzb+s1h+vD4FZMU2aOT2oDB2ceTwXSar\nVK5bJ0wdMe0s4t6/96Fn7i5dp+rY6cAxHEigqpfvxSnV1enPICCIPbkM9TuFmyu1\nEEtgjNK72fozzZveo9ih1G8rs02ylO3udN9Lk+t/yla5YVjkcAz/MP8LoA9cBwCI\noMQpYuFE20IRjMXQ1LHhUHtPwlkPc4D3c9yklkV5SsKHDR01GN4CSf59vsKt8otX\ndWMF9woAn2xUB9WdMyWfqrQ/5MNG9z1pvvhyTqT0awnymiNfCZzJzSZAPm/L9SeQ\nNu/vZ1FgpG5ahZXEDTOdlk1hnJHz5FibdAwPLHF46uxGJTYK0SJaYhu3Z2XXDyVe\n1qJgvhaa73r2xRAnWEnmh1OdlR3fAlii1TlFVVLzYvBEeYCbLViR/NKA8YW1wLrW\nqSEHcrEQGhjkS0ycOBS4xl5sueWMERpy6SI8oQBo6ESTqIwjSppwRL58rdd05hhj\nAbV6GzjXO9TPT13n3SAuutLgdtmDzPI7MY6dYbGFr4lmjCoBQ7LIujhq55lodadG\n1jY2BjzN7NWuwUd1Cp+AsKBnfIOmR2MXgnfzen68+vxhhtsW744VP6+sv25LNNw3\n/mKv8+R4mMVtwrovN+sX+VymzhwWTK3PlG1kqRKC5dtpe1CFq5mYiFdRNQpdnM4x\ng/+vg+3PtFH0+PDMkPffe6xUW4OA/OoueakJ3ZzHPR6bCEm/+4BAldzutBXUTj+N\nv9Hdho/F9Bv3xMM8FwuQgGnb9VL63yp+t1nqiSyYi/WWuI5pu+t+gHZG9TcC6/ZG\naOKs3tSOuwEZQIyXOuPNkH2dkgNHUklDGI5eWzjauaWslIWRERx5guDdqZwHGFRW\nY4Ct/3lzbNN/BtRh0giwfBId+K2QlWXq8nc8yT6LJl72oxOKMnnNAjNqK2AQqq/t\nlAyCONXayLO7YjC0200DlyFebs6qr/uuxl5cN55SDKmjXbv9RWULpqf7plYBYFpX\nGMUYUXqLxFBLcCgVY5fHZ+r6OmX9+dtdulu44t7JE3DzieJ3AZZCPAQBJOr8p2RH\nve98tUb9mSNuR3/aJWsbYizsDGlfLU3KSpUgSOEOz8wBM3Dt6ICKs4LSGxDd5PLC\nUDVbu2p15qzyVeol4iOxTYHSdX6Iy3r1OW8S5t/l2GWK3dnLWjJFj5tqUAj/BTN2\nw8YZjZkIe585FVe2/pVY2v5jMROfKkVbCjfWl48Xvtk86qxhFqXRWu39AygkiqN5\n1xzvb+7QfKSp4RmHeRZGl+bFXNM0jqcQYmizcGl4C8jbh/CxAjvXsIV5YWjqTZNE\nDcGbU/rwmYbilSOu90QMQT+W1ezzuwraX3W0y0AwgdIsEWnS4flTiDo=\n-----END ENCRYPTED PRIVATE KEY-----\n",
        "privatekey_pass": "q"
    }
}
```

## Instructions
1. Use the SQLAlchemy URL above to connect to your Snowflake database
2. Use the Security JSON configuration for authentication
3. The private key is already formatted with escaped newlines for direct use
