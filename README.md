Thanks to particle4dev:upload-avatar
### Create template and install on the application
    {{> editYourAvatarModal}}

### Call modal Image
`
	"click a.profilePict": function (e, tpl) {
		e.preventDefault();

		Session.set('UI_Width',256);
		Session.set('UI_Height',256);
		Session.set('UI_Document',Meteor.users);
		Session.set('UI_IDdata', Meteor.userId());
		Session.set('UI_Kolom', 'profile.fotoMember');

		$('#editYourAvatarModal').modal();
	},
`


### Demo
[![ScreenShot](https://i1.ytimg.com/vi/GSaJPWG3vY8/mqdefault.jpg)](http://youtu.be/GSaJPWG3vY8)
