/// <summary>
/// An enthusiastic IT student seeking opportunities to grow in backend and full-stack development. 
/// Passionate about innovative and user-friendly digital solutions. Strong background in mobile apps, 
/// backend systems, and UI/UX design.
/// </summary>
public class PROFILE
{
    public const string NAME = "Jule Brian R. Mortalla";
    public const string TITLE = "Information Technology Student";
    public const string LOCATION = "Landing, Catarman, Lilo-an, Cebu";
    public const string EMAIL = "julebrianmortalla@gmail.com";
    public const string PHONE = "09752512595 / 09496210316";
}

public enum LANGUAGES
{
    English,
    Tagalog,
    Cebuano
}

public enum SKILLS
{
    Kotlin,
    PHP,
    Java,
    C#,
    ReactJS,
    Laravel,
    .NET,
    Android,
    Figma,
    VisualStudioCode,
    AndroidStudio
}

public enum EDUCATION
{
    UNIVERSITY_OF_CEBU_BANILAD_BSIT_2021_Present,
    UNIVERSITY_OF_CEBU_SHS_BANILAD_STEM_2017_2019
}

public static class PROJECTS
{
    public static void SoleMateSystem() =>
        Console.WriteLine("Back-End Developer | 2024 | Laravel | Footwear inventory system");

    public static void EcommerceWebsite() =>
        Console.WriteLine("Full Stack Developer | 2024 | ReactJS | Online shopping platform");

    public static void CraftopiaApp() =>
        Console.WriteLine("Programmer | 2023 | Mobile Application");

    public static void EnrollmentSystem() =>
        Console.WriteLine("Full Stack Developer | 2023 | .NET | School system");
}

public static class ABOUT_ME
{
    public static void Summary()
    {
        var motivation = "Building user-friendly & innovative solutions.";
        var focusAreas = new[] { "Mobile App Dev", "Backend Dev", "UI/UX Design" };
        var drive = "Strong desire to continuously learn and take on new challenges.";
        Console.WriteLine($"{motivation}\nFields: {string.Join(", ", focusAreas)}\n{drive}");
    }
}
