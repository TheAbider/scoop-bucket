# TheAbider Scoop Bucket

Scoop bucket hosting [RackStack](https://github.com/TheAbider/RackStack)
and any future tools by [@TheAbider](https://github.com/TheAbider).

## Add the bucket

```powershell
scoop bucket add rackstack https://github.com/TheAbider/scoop-bucket
```

## Install RackStack

```powershell
scoop install rackstack
```

## Update

```powershell
scoop update rackstack
```

The manifest's `checkver` + `autoupdate` blocks track the
[RackStack releases page](https://github.com/TheAbider/RackStack/releases)
so updates land here automatically.

## Verify

```powershell
$exe = (scoop which rackstack.exe)
gh attestation verify $exe --owner TheAbider
```

## License

The manifest is MIT. Licensing of the installed software is per its
own LICENSE — RackStack is MIT.
