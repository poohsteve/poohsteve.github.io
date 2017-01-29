## 환영합니다. 테스트 page입니다.
You can see my works at the [my_naverblog](http://kanghans94.blog.me/) to contact with me -> amazingstevekang@gmail.com


// Examples:
// Image links displayed as a group
$('a.gallery').colorbox({rel:'gal'});

// Ajax
$('a#login').colorbox();

// Called directly, without assignment to an element:
$.colorbox({href:"thankyou.html"});

// Called directly with HTML
$.colorbox({html:"<h1>Welcome</h1>"});

// Colorbox can accept a function in place of a static value:
$("a.gallery").colorbox({rel: 'gal', title: function(){
  var url = $(this).attr('href');
  return '<a href="' + url + '" target="_blank">Open In New Window</a>';
}});



