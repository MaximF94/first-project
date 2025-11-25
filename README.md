# Тест редактирования readme.md

## _курсив_


## __жирный__


''' java
 void changeStepGoal() {
        System.out.println("Введите новую цель: ");
        int aNewGoalByStepsPerDay = scanner.nextInt();

        if (aNewGoalByStepsPerDay <= 0) {
            System.out.println("Цель шагов за день должна быть больше нуля!");
            return;
        }

        goalByStepsPerDay = aNewGoalByStepsPerDay;
    }
'''