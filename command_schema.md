```
exports.run = async (client, message, args) => {
  //Code...
};

exports.help = {
  name: "cmd_name",
  guildOnly: true, // false olur ise DM'den de kullanılabilir bi hal alır | true olur ise sadece sunucuda kullanılabilir bir halde olur
  perms: ['MANAGE_MESSAGE', 'ADMINISTRATOR'], // yetki ayarları
  aliases: ['aliases']
};
```