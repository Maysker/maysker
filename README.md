## About Me: Full Stack Developer
```php
class FullStackDeveloper extends ProjectManager {
  public $name = "Adam Gazdiev";
  public $location = "Belgium";
  public $currentStatus = "Looking for new opportunities in web development";

  public function myProfile() {
    return [
      'name' => $this->name,
      'role' => 'Full Stack Developer',
      'location' => $this->location,
      'status' => $this->currentStatus,
    ];
  }
}

$myProfile = new FullStackDeveloper();
echo $myProfile->myProfile();

```
## Career Journey
```javascript
async function fetchMyCareerPath() {
  const education = await getEducation();
  const experience = await getWorkExperience();
  const managementSkills = await getManagementSkills();
  const technicalSkills = await getTechnicalSkills();

  console.log(`Education: ${education}`);
  console.log(`Work experience: ${experience.join(', ')}`);
  console.log(`Management Skills: ${managementSkills.join(', ')}`);
  console.log(`Technical Skills: ${technicalSkills.join(', ')}`);
}

fetchMyCareerPath();

function getEducation() {
  return 'Master’s degree in International Relations, People’s Friendship University of Russia';
}

function getWorkExperience() {
  return [
    'Project Management',
    'Strategic Planning and Execution',
    'Cross-Functional Team Leadership'
  ];
}

function getManagementSkills() {
  return ['Time Management', 'Coordination', 'Team Leadership'];
}

function getTechnicalSkills() {
  return ['Front-end Development', 'Back-end Development', 'Database Management', 'Version Control'];
}

```
## Status
```sql
SELECT * FROM jobs WHERE candidate = 'Adam Gazdiev' AND status = 'active';
```
## Contacts
- 📧 Email: a.gazdiev [at] gmail [dot] com
- 💼 LinkedIn: [Adam Gazdiev](https://www.linkedin.com/in/adam-gazdiev/)

<div align="center">
<h1 >:computer:My Tech Stack</h1>
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,bootstrap,angular,js,ts,laravel,mysql,postman,nodejs,php,vscode" />
  </a>
</p>
</div>

