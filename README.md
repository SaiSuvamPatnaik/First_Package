# Custom-Toast Box

My first trial package which I tried to push into pub.dev

## Getting Started

This Package is all about generating a toast box in your project.

## Procedure

1. Just Include the following dependency in your pubspecs.yaml file

    dependencies:
        trial_package: ^0.0.1

2. Install the packages into your project by writing the following command

    $ flutter pub get

3. Now Import it into your dart file where you want to create a Toast box

    import 'package:trial_package/trial_package.dart';

4. Now You are Free use.

5. Just Include this code inside the onTap() Function

    CustomAlertBox.showCustomAlertBox(
                  context: context,
                  willDisplayWidget: Container(
                    child: Text('Text Of Your Wish'),
                  ));
