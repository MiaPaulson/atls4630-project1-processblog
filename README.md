# Mia Paulson Process Blog

## Milestone 1

Here is the repository we are using:
[project1-repo](https://github.com/CDAWGSWAGMAN/ATLS-4630-Project-1)

Here is our project 1 proposal:
[project1-proposal](https://o365coloradoedu-my.sharepoint.com/:w:/g/personal/mipa2824_colorado_edu/EX9IurRvKKdLlSEHVn_e0GcB2Sgf49iyLpLMWYlKwDj0Wg?e=qd1BOs)


Here is our mid-fidelity prototype of what we want our final product to look like!

<img width="488" height="247.66" alt="image" src="https://github.com/user-attachments/assets/c3927da6-c918-449c-80b4-487969958b02" />

Here is our prototype separated by UI Hierarchy:

<img width="416" height="242.66" alt="image" src="https://github.com/user-attachments/assets/f35a470e-75c1-427f-8521-ecf889ce31e9" />


Data we need/keeping track of:
1. User input
2. Drink info from API (currently viewable from filters)
3. Cart
4. Favorites


## Milestone 2
My job for Milestone 2 was to work on the Search and Filter section that's "static". I cross-referenced the others' code for my css ideas and little refreshers on react since I'm still super new to it. I also used our Figma prototype as a reference to make the look of our final product similar. I also used ChatGPT to help with specific CSS coding - I don't know every specific syntax, so I asked for some help with what I was envisioning.


Right away I knew I needed:
1. Searchbar
2. Dropdown for searchable types
3. Different filter buttons
4. Title and header bar


The CSS for the Searchbar + Dropdown presented in our Figma was very difficult to do on my own, so ChatGPT was a big helper for this specific task. I figured out that you can hide the outline AND the overflow, making both interactions look like one seemless bar.

Doing the research for a "dropdown" for sections to specify what the user is looking up in the search bar is a bit confusing. It looked like I'm going to have to make a new branch of the search and filter for the dropdown specifically, like how our cart is set up. So I made a new folder and file inside the SearchFilter section as a new branch.

Actually, after coding it, decided to NOT make Dropdown its own page. Just threw it in on the SearchFilter page.

I think I did it all right?? This is just the first milestone so that's good, but I'm just hoping I'm understanding what to do correclty. Since I was the last one able to work on it, below is what the static page looks like once I'm done:

<img width="952.66" height="519" alt="image" src="https://github.com/user-attachments/assets/ee372eea-8af3-4777-9756-a8d69f0381d5" />


Per usual with this code stuff, this part of the assignment (which is the easiest section, compared to the ones my partners did) took me a very long time. But, I'm practicing and getting better!


## Milestone 3

Decided to start with State before API. Below are the States used for the InputValue section:
1. Input - string
2. Dropdown open/closed - boolean
3. Dropdown value - button option, one at a time
4. Filters being used - boolean

I knew I wanted to have the "enter" key be the way to look up specific aspects of the drinks, so I had some convos with ChatGPT to walk me through how to code it and what each section was doing. With the CheckList assignment I had a button be pressed instead, but I wanted to go this extra step for this project. I worked with the boolean states for the CheckList, so that was easy to look back on and figure out how to apply it here.

At first for the filters, I was going to add the values into a list of filters. However, I realized that by doing that I would have to create another functionality to remove the filters from the list. So, I decided instead to have each filter be a boolean of "being used", yes or no. I did a similar style as the Checkbox I used for the last project - when the filter is selected, it changes color to indicate to the user that they have that filter on.

I also made sure that once a dropdown option was chosen, the dropdown disappeared. Right now its position isn't great since it moves along with different computer screens (not always right under the search bar) but I want my groupmates to have my states so I'll wait to fix that until later.


### Final Deliverables
Here is the repository (just posted again down here as a final deliverable) we are using:
[project1-repo](https://github.com/CDAWGSWAGMAN/ATLS-4630-Project-1)

Here is the vercel of our app:
[project1-vercel](https://atls-4630-project-1.vercel.app/)
