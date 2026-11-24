/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
double* convertTemperature(double celsius, int* returnSize) {
    double* ans = (double*)malloc(2 * sizeof(double));

    ans[0] = celsius + 273.15;      // Kelvin
    ans[1] = celsius * 1.80 + 32;  // Fahrenheit

    *returnSize = 2;

    return ans;
}
