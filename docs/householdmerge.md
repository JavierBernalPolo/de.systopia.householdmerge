#**CiviCRM Extension to merge contacts into households**


- Development Status: stable
- Used for: CiviCRM Extension to support you with creating and maintaining households.
- CMS Compatibility: 4.6, 4.7, 5
- Git URL: [click me](https://github.com/systopia/de.systopia.householdmerge)
- Fully Qualified Name: de.systopia.householdmerge
- Author: Systopia.


#**CiviCRM Extension to merge contacts into households**

CiviCRM Extension to support you with creating and maintaining households. It is currently under development, so feel free to contact us for the bits that are still missing - or simply contribute the implementations.

The extension allows you to choose on of three household modes:

1. merged: all contacts get merged into the household contact, the original contacts will be deleted
2. linked: all member contacts are connected to the household via 'member of' relationship
3. hierarchy: member contacts are connected to the household via 'member of' or 'head of' relationship. There is only one head.

The extension so far gives you three different tools:

1. create from search result: Select the contacts in a search result and choose the action "join to household". Currently only for mode 'merged'.
2. find households: Scan your database for potential new households (based on last name and address). Currently only for mode 'linked' and 'hierarchy'.
3. check households: Cron job to check your existing households for integrety and consistency. Currently only for mode 'linked' and 'hierarchy'.

First stage (merged households on search results) funded by [[Forum Ziviler Friedensdienst e.V.]](http://www.forumzfd.de/), contact person Bendikt Kaleß, kaless (at) forumZFD.de.

Second stage (linked and hierarchy tools) funded by [[muslimehelfen e.V.]](https://www.muslimehelfen.org/), contact person Fouad Rebbah, Fouad.Rebbah (at) muslimehelfen.org

For ideas and questions feel free to contact them.
