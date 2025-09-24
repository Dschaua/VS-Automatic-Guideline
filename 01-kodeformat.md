## PascalCase til klasser, funktioner og komponenter

### C#

    public class UserProfile { }

    public void CalculateTotal() { }

    const LoginForm = () => { ... }

## camelCase til variabler og parametre

### C#

    string userName;

    void GetUser(int userId) { ... }

## \_camelCase til private fields i C#

### C#

    private readonly IUserService _userService;

## snake_case til SQL-tabeller og kolonner

### SQL

    SELECT first_name FROM user_profile;

## Kommentarstruktur:

### C#

     /// <summary>Henter brugerens profil.</summary>

     public User GetUser(int id) { ... }

### JS/TS:

    JSDoc

### TypeScript

    /** Henter brugerdata fra API */

    function fetchUser(id: string): Promise<User> { ... }

### CSS

    /** Centrerer indholdet */

    .container {

    display: flex;

    justify-content: center;

    }
