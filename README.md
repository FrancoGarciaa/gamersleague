# gamersleague
Sitio Web de una pagina de torneos

.soporte-details section{
    grid-area: section;
}
.soporte-details aside{
    grid-area: aside;
}
.soporte-details {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 2fr 2fr 0.5fr;
    grid-template-areas: 
        "section aside"
        "section aside"
        "section aside"
        "section aside";
    grid-column-gap: 1rem;
    grid-row-gap: 1rem; 
    width: 100%;
    height: 100vh;
}