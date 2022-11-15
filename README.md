# certifica-o-rlet media = (atletas[0].notas)
media.sort(function(a, b) {
    return a - b;
});
media[0] = 0
media[media.length - 1] = 0

let soma = media.reduce(function(total, atual){
    return total + atual
},0)
console.log(media) // [ 0, 8.42, 9.34, 10, 0 ]
console.log(soma/3) // a media deu 9.253333333333332 do primeiro atletaeadme
