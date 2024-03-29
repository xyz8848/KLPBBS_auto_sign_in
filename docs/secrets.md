# [KLPBBS_auto_sign_in](https://github.com/xyz8848/KLPBBS_auto_sign_in)
## Secrets

### USERNAME
- **描述**：苦力怕论坛用户名
- **必填**：是
- **值型**：字符串
- **示例**：`admin`

### PASSWORD
- **描述**：苦力怕论坛密码
- **必填**：是
- **值型**：字符串
- **示例**：`admin123456`

### SWITCH_USER
- **描述**：当用户组到期时切换至普通用户组（0=关闭，1=开启）
- **必填**：否
- **值型**：整数
- **示例**：`1`

### RENEWAL_VIP
- **描述**：当 VIP 用户组到期时续费（0=关闭，1=开启）
- **必填**：否
- **值型**：整数
- **示例**：`1`

### RENEWAL_SVIP
- **描述**：当 SVIP 用户组到期时续费（0=关闭，1=开启）
- **必填**：否
- **值型**：整数
- **示例**：`1`

### DEBUG
- **描述**：调试模式（0=关闭，1=开启）
- **必填**：否
- **值型**：整数
- **示例**：`1`

### MAIL_ENABLE
- **描述**：签到后邮件提示（0=关闭，1=开启）
- **必填**：否
- **值型**：整数
- **示例**：`1`

### MAIL_HOST
- **描述**：SMTP 服务器
- **必填**：否
- **值型**：字符串
- **示例**：`smtp.example.com`

### MAIL_PORT
- **描述**：SMTP 端口
- **必填**：否
- **值型**：整数
- **示例**：`465`

### MAIL_USERNAME
- **描述**：邮箱账号
- **必填**：否
- **值型**：字符串
- **示例**：`admin@example.com`

### MAIL_PASSWORD
- **描述**：邮箱密码
- **必填**：否
- **值型**：字符串
- **示例**：`admin123456`

### MAIL_TO
- **描述**：用于接收通知的邮箱
- **必填**：否
- **值型**：列表
- **示例**：`['admin@example.com']`，`['admin1@example.com', 'admin2@example.com']`

### SERVERCHAN_ENABLE
- **描述**：签到后Server酱提示（0=关闭，1=开启）
- **必填**：否
- **值型**：整数
- **示例**：`1`

### SERVERCHAN_KEY
- **描述**：Server酱 SendKey
- **必填**：否
- **值型**：字符串
