## App Design Analysis
**1. Facebook Mobile App**  

* `News Feed Tab
 `(Tab Bar Controller)
   	* if not logged in sign in/ register page  (modal)
   	* newsfeed scrolls to display posts
   	* click post to display detail
   	* click pictures to enlarge
   	* newsfeed contains tab bar that switches betweeen 
      newsfeed/Requests/messenger/notifications/more
   * search bar to search profiles within facbook
      

* `Select Request tab to view friend requests accept`(Table View Controller)
	* accept new friend request 
	* send new friend request
	* remove people you may know
	

* `Select Messenger to view new messages`(Table View Controller)

	* selecting tab opens messanger app if messenger app is installed
* `Select notification tab to view notifications`(Table view Controller)
	* scroll through new and previous notifications
	* select notifications to view detial (push)

* `Select more tab to view more options`(Table View Controller)
	* select option buttons to view detail(push)
	* select settings button to view settings


	

**2. Instagram**


* `Login or Register` (Modal)

  * `Instagram Photo Feed`(Tab bar controller)

     * Tap like button to Like Post(navigation push)

	  * Tap comment button to Comment on Post (Push Segue)
		  	- comment button opens comment

		* Tap Send button to send post to followed user 
			- sends selected post to target 
 * `Search and Browse tab`
	   * Search bar and recently viewed 
	   
	   * Search bar diplays search options(collection view)
	   
	   * Browser shows photos you may like 
	   		* tap photo to view detail 
 * `Photo Tab`(toolbar item)
 		* adds photo or video from user library
 		* uses camera to take photo
 		* uses camera to record video 
 * `Activity Tab`(Table View)
 		* shows activity of users user follows
 		* shows other users who have liked users photo or have started following user
 		* click on other user to view profile
 * `Profile Tab`(scroll view)
 		* Edit Profile
 		* View posted photos
 		* Tap photos to view details
 		* View user statistics 		 
	   			 		

		
**3. SnapChat**

* `Login or Register` (modal)
#
	* `Take Snap` ()

		* Take photo or video 

		* Send photo or video to target user 

		* Choose camera setting (flash,light mode, front or rear) 

		* Recieved Snaps  

		* Stories 		

**4. Hearthstone: Heroes of Warcraft**

* `Login or Register` (modal)
#
	* `Main Menu` (modal)

		* Tap Play button to start match

		* Tap Solo Adventure button to open Practice menu 

		* Tap Quests button to view daly quests 

		* Tap Shop button to view shop menu 

		* Tap Open Packs button to view open packs menu (modal Tableview)
		* Tap My Collection to view card collection menu
		
		* Tap Friends list
		 
		* Tap Settings	

**5. Swarm**

* Login or Register (Modal)
#
	* `Activity Feed` (Tableview)

		* Search bar (navigation push)

		* Tap check-in to view detail(modal)

		* Check-IN (Tableview with push details)

		* Leaderboards (table view)

		* Inbox

		* Profile 	
		
		
		
**6. The Executive**

* `Intro Scene` (modal)
#
	* `First Stage` (scroll view)

		* User Input to perform action

		* Tap top of screen to punch/kick high

		* Tap bottom of screen to punch/kick 
      
		* Screen scrolls left to right as player progresses through stage

		* STAGE CLEAR message when clear conditions are met(modal table view)

		* Choose restart stage or continue to next stage 	
		
		
**7. hulu**

* `Home Tab` (modal)(table view)
#
	  * `Feauture Film `

		* Scroll left to right SHOWS YOU WATCH
		
		* Tap Show to view details

		* Search Shows
      
		* Tap feature film to play film

		* STAGE CLEAR message when clear conditions are met

		* Choose restart stage or continue to next stage 

		
			
**8. Miitomo**

* `Loading Screen` (modal)
#
	* `My Room` (tab bar controller)

		* Tap character to interact 

		* Tap Recent to show recent answered questions

		* Tap My answers to show user answers 
      
		* Tap Friends to show user friends list

		* Tap Shop to bring show Shop Menu

		* Tap Menu to bring up main menu  	
				
		
		
		
**9. YouTube**

* `Home Page` (Table view controller)

	   * Tab video to Play video and show detail 

		* Tap Trending to show trending videos

		* Tap Accout to view account 

		* Tap bottom of screen to punch/kick 
      
		* Search videos with search bar

		* Tap settings to view options

		
		
**10. Adobe Photoshop Lightroom for iPhone**

* `Lightroom Photos` 
#
	* `First Stage` 

		* Add photos from user library

		* Take Photo

		* View photos in lightroom library
      
		* Sync to Lightroom Cloud

		* Organize photos by options

		* Creat Collection

		
			
**11. Google Cast**

* `Sign in` (modal)
#
	* `Home` (table view controller)

		* Search movies and shows

		* Tap show to open in target app

		* Tap Devices to add and manage devices 
      
		* Tap Get Apps to show compatable apps

		* STAGE CLEAR message when clear conditions are met

		* Choose restart stage or continue to next stage 

		
**12. NETFLIX**

* `Account/Sign In` (modal)
#
	* `Home` (table view)

		* Tap show/movie to show more detail (push segue)

		* search movies/shows

		
				