# task-6
flutter
flutter Flutter Screens (home - Login - OTP)

This Flutter project includes three main authentication screens for logging in using a phone number, with a simple and clean UI. ✅ Screens:

    home Screen

    A welcoming screen. Contains a "Let's Get Started" button. Navigates the user to the Login screen.

Navigator.pushNamed(context, '/login');

    Login Screen

    Input for phone number and password. Login button that navigates to the OTP screen. Link to navigate to the Sign Up screen.

Navigator.pushNamed(context, '/otp');

    OTP Screen (Verification)

    Input for the verification code sent to the phone. Displays the entered phone number. Can be extended to send/verify OTP using Firebase or another provider.

Files:

home_screen.dart
login_screen.dart
otp_screen.dart

Navigation Between Screens:

routes: { '/': (context) => const HomeScreen(), '/login': (context) => const LoginScreen(), '/otp': (context) => const OTPScreen(), '/signup': (context) => const SignUpScreen(), }

Future Notes:
<img width="937" height="792" alt="image" src="https://github.com/user-attachments/assets/dea32905-6a00-4b43-a7df-874f73399793" />
