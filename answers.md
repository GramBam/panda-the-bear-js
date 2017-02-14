$($('img')[0]).attr('src', 'https://placekitten.com/g/400/400');

$($('img')[1]).attr('src', 'https://placekitten.com/g/325/225');

$('h1').text('Graham');

$("#employment .info-title").text('Unemployed');

$('#time-travel').parent().remove();

$('body').css('color', 'red');

$('.highlight').css('color', 'blue');

$('h1').css('font-family', 'monospace');

$('p.action-icon').css('color', 'black');

$('#name').attr('placeholder', 'Identify Yourself');

$('#message').attr('placeholder', 'State Your Business');

$('#name').attr('value', 'Your Nemesis');

$('#email').attr('value', 'koalathebear@gmail.com');

$('#submit').attr('value', 'En garde!');

$('#submit').attr('disabled', 'disabled');

$('.bio-info').empty();

$('#right-image img').clone().appendTo('form');

for (i = 0; i < 10; i++) { $('#right-image img').clone().appendTo('form'); }


var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);
var rightSpan = document.createElement('span');
var date = document.createTextNode(Date());
rightSpan.appendChild(date);
listItem.appendChild(rightSpan);
