
 <pre>
                                        ___           ___           ___       ___       ___     
                                       /\__\         /\  \         /\__\     /\__\     /\  \    
                                      /:/  /        /::\  \       /:/  /    /:/  /    /::\  \   
                                     /:/__/        /:/\:\  \     /:/  /    /:/  /    /:/\:\  \  
                                    /::\  \ ___   /::\~\:\  \   /:/  /    /:/  /    /:/  \:\  \ 
                                   /:/\:\  /\__\ /:/\:\ \:\__\ /:/__/    /:/__/    /:/__/ \:\__\
                                   \/__\:\/:/  / \:\~\:\ \/__/ \:\  \    \:\  \    \:\  \ /:/  /
                                        \::/  /   \:\ \:\__\    \:\  \    \:\  \    \:\  /:/  / 
                                        /:/  /     \:\ \/__/     \:\  \    \:\  \    \:\/:/  /  
                                       /:/  /       \:\__\        \:\__\    \:\__\    \::/  /   
                                       \/__/         \/__/         \/__/     \/__/     \/__/    


</pre>


<pre>

class TresorKone
{

    private $username = 'TresorKone';
    private $name = 'Koné Trésor';
    private $role = 'Backend Developer';
    private $website = '...';
    private $howToReachMe = '...';
    private array $languageSpoken = ['en_US', 'fr_FR'];
    private array $code = [
                        'frontend' => ['HTML', 'CSS', 'JavaScript', 'Boostrap', 'TailWind'],
                        'backend' => ['Symfony', 'PHP'],
                        'database'=> ['MySQL', 'MariaDB'],
                        'tools'=> ['VS Code', 'Docker', 'GitHub Actions', 'Heroku', 'Apache'],
                        'misc'=> ['SCRUM', 'GNU/Linux'],
    ];
    private array $architecture = ['SPA_Ajax', 'MVC'];


    public function getName(): ?string
    {
        return $this->name;
    }

}

$my_name = new TresorKone();

echo 'my name is' . ' ' . $my_name -> getName(); //return 'my name is Koné Trésor'

</pre>



<!---
TresorKone/TresorKone is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
