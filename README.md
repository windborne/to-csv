# to_little_r

This utility queries the [WindBorne API](https://windbornesystems.com/docs/api) and converts the files to CSV
While it works out of the box, we encourage you to adapt it to your needs.

For both methods of running, you will need to set the environment variables `WB_CLIENT_ID` and `WB_API_KEY`.
If you do not have these, you may request them by emailing data@windbornesystems.com.

## Installing dependencies

```shell
pip3 install pyjwt requests
```

## Running

```shell
python3 wb_to_csv.py START_TIME

# Example:
python3 wb_to_csv.py 2024-11-11_00:00
```

This will query the WindBorne API for data from `START_TIME` to the present and write it to the current working directory.


