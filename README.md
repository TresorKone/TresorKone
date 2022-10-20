
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

<pre>
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        Download my CV:
        - English version in <a href="./Docs/TresorKone CV ENG-vers.pdf">PDF<a> or in <a href="./Docs/TresorKone CV ENG-PNG.png">PNG<a>
        - French version in <a href="./Docs/TresorKone CV FR-vers">PDF<a> or in <a href="./Docs/TresorKone CV FR-PNG.png">PNG<a>
    </body>
    </html>
</pre>



<!---
TresorKone/TresorKone is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
