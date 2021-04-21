# SPA - Single page application

#  useEffect(()=>{
#  fetch('http://localhost:3333/episodes')
#  .then(Response=>Response.json())
#  .then(data => console.log(data))
#  },[])
----------------------------------------------

# SSR - Server side render

#  export async function getServerSideProps() {
 # const response = await fetch("http://localhost:3333/episodes");
 # const data = await response.json();

  # return {
  #  props: {
  #    episodes: data,
  #  },
 ## };
------------------------------------------------

# SSG - Static side generation
