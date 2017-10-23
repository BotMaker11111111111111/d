 bot.on("serverNewMember", function (server, user) {
           mybot.addMemberToRole(user, server.roles.get("name", "Member"), function (err) { if (err) console.log(err) })
