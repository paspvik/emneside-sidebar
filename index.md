{% include top-box.html %} <!-- Kode for å inkludere boksen på toppen av siden. Se _config.yml for å gjøre endringer. -->
<!-- Gjør endringer under her -->





## Kursbeskrivelse 

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

$x\cdot (1+\frac{r}{n})^{T\cdot n}$

## Faglærerinfo
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Pensum
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Forelesningsplan
- [Timeplan](timeplan.md)
- Innhold
- Ressurser
  - Pensum
  - Notater
  - Video
  - Øvinger
  - Kode
  - Lenke til Jupyter
  - FAQ

## Innlevering
- Timeplan
- Oppgaver
- Ressurser
- Lenke til innlevering (Wiseflow)
- Lenke til CV side
- Lenke til GIT

## FAQ

## Kursevaluering
- Midtveis
- Slutt

## Equations

$x\cdot (1+\frac{r}{n})^{T\cdot n}$




<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>



<ul id="myList"></ul>

<script>  
  
  
h2_tags = document.getElementsByTagName('h2');

var lenke_titler = new Array();
var lenke_lenker = new Array();

  for (i = 0; i<h2_tags.length; i++) {
       lenke_titler.push(h2_tags[i].getAttribute('id'));
  };

   for (i = 0; i<h2_tags.length; i++) {
       lenke_lenker.push("#" + lenke_titler[i]);
  };                               

                                                              
console.log(lenke_titler);
console.log(lenke_lenker);  
       
lenke_lenker.forEach((x,i) => {
  sidebar.insertAdjacentHTML("beforeend",`<a href="${x}"><div>${lenke_titler[i]}</div></a>`)
})
                             
</script>




