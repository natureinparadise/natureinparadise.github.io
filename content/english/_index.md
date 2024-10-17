---
############################### Banner ##############################
banner:
  enable : true
  bg_image : "images/landscape/canopy_understory.JPG"
  bg_overlay: true
  title : "NATURE .IN .PARADISE"
  content : "Research, Multimedia, and Outreach by Dave Klinges"
  button:
    enable : true
    label : "Learn more about Dave"
    link : "about"

############################# About #################################
about:
  enable : true
  title : "[Research: Thermal Ecology meets Landscape Ecology](/research)"
  description : "A record of the meditations, murmurs, and misadventures of Nature Dave in his pursuit of ecological knowledge."
  content : "Despite hundreds of years of observational, experimental, and simulative work, we still have much to learn about our environment. To uncover and disseminate this endless knowledge is critical given the state of anthropogenic global change, as the immense biodiversity and undomesticated landscapes that are the source of natural beauty are imperiled. This website serves to record the endeavors of Dave Klinges on fulfilling these missions."

  button:
    enable : true
    label : "View Research Program"
    link : "research"

  image : "images/wildlife/ameerega_trivittata.png"


######################### Portfolio ###############################
portfolio:
  enable : true
  bg_image : "images/landscape/shenandoah_forest.png"
  title : "[RESEARCH PROGRAM](research)"
  content : " Furthering knowledge of natural systems requires integrative research that combines field observations, experiments, models, and simulation.

  My research leverages cutting-edge modeling tools, remote sensing methods, and big data to develop and test ecological and geographical hypotheses.


  <br>
  "
  button:
    enable : true
    label : "View Research Program"
    link : "research"

############################# Service ############################
service:
  enable : true
  # service content comes from "content/*/service.md" file

############################ call to action ###########################
cta:
  enable : true
  bg_image : "images/landscape/Serra_Estrela.JPG"
  title : "  If research is the eyes of the scientific community, outreach is its voice: positive change requires proper communication and motivation.


  One form of conveying the importance of conservation work is through film and photo. See the gallery for some of Nature Dave's work developing multimedia products to share some of the amazing wildlife and scenes he's experienced.

  "
  button:
    enable : true
    label : "View Gallery"
    link : "project"


############################# Funfacts ###############################
funfacts:
  enable : true
  title : "[Ongoing Events: Blog](blog)"
  description : "A handful of updates on what's been going on"

  funfact_item:
    # funfacts item loop
    - icon : "ion-ios-chatboxes-outline" #ionicon pack v2 : https://ionicons.com/v2/
      name : "Cups Of Coffee"
      count : "99"
      
    # funfacts item loop
    - icon : "ion-ios-glasses-outline" #ionicon pack v2 : https://ionicons.com/v2/
      name : "Articles Written"
      count : "45"
      
    # funfacts item loop
    - icon : "ion-ios-compose-outline" #ionicon pack v2 : https://ionicons.com/v2/
      name : "Projects Completed"
      count : "125"
      
    # funfacts item loop
    - icon : "ion-ios-timer-outline" #ionicon pack v2 : https://ionicons.com/v2/
      name : "Combined Projects"
      count : "200"

  testimonial_slider:
    # testimonial item loop
    - name : "[Conservation Tech](blog/mada_conservation_tech)"
      image : "images/people/nature_greenlee_ambodivoahangy.png"
      designation : "Conservation"
      content : "[Engaging with Malagasy stakeholders to understand how to implement conservation tech](blog/mada_conservation_tech)"
                
    # testimonial item loop
    - name : "[Dave Klinges Defends Dissertation](blog/defense)"
      image : "images/research/klinges_defense2.jpg"
      designation : "Research"
      content : "[A successful PhD defense!](blog/defense)"
                
    # testimonial item loop
    - name : "[Data Management Workshop in Madagascar](blog/mnp_workshop)"
      image : "images/outreach/mnp_workshop/IMG_0782_crop.JPG"
      designation : "Outreach"
      content : "[Capacity building at Madagascar National Parks](blog/mnp_workshop)"

    # testimonial item loop
    - name : "[Patagonia April 2024](blog/patagonia)"
      image : "images/people/patagonia_nature_katie1.png"
      designation : "Travel"
      content : "[A break from research: backpacking and hiking](blog/patagonia)"

    # testimonial item loop
    - name : "[Species on the Move 2023](blog/sotm2023)"
      image : "images/research/sotm2023_1.jpg"
      designation : "Research"
      content : "[An international conference exploring global change-induced range shifts](blog/sotm2023)"

---

Here’s a more polished and concise version of the feedback:

---

- Excess Files & Folders: The project contains many unused files and directories, increasing its size unnecessarily.
- Automation for Deployment: Instead of manually uploading build files (`public` folder) to GitHub, we can set up an automated GitHub Pages deployment. By using GitHub Actions, the site will automatically build and deploy whenever you push changes. This reduces manual effort. However, to use this feature, your repository must be public.

- Multilingual Configuration Issues: The multilingual setup is inconsistent. For example, the homepage isn’t properly configured for multiple languages. We can implement a fully functioning multilingual feature across the entire site.

- Empty UI Sections: There are pages where empty sections still appear, even when no content has been added. This negatively impacts user experience and should be fixed.

- Configuration and UI Discrepancies: Some configuration files have been merged or altered, which has led to UI issues when compared to the live version of the site. We can review and adjust the configurations to restore proper functionality.
